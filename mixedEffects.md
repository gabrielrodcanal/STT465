library(BGLR)
data(mice)
head(pheno.mice)
head(mice.pheno)
table(mice.pheno$cage)
head(mice.pheno)
Z=as.matrix(model.matrix(~GENDER+CoatColour,data=mice.pheno)))
Z=as.matrix(model.matrix(~GENDER+CoatColour,data=mice.pheno))
head(Z)
dim(X)
X=as.matrix(model.matrix(~GENDER+CoatColour,data=mice.pheno))
dim(X)
y=mice.pheno$Obesity.BMI
y=scale(mice.pheno$Obesity.BMI)
var(y)
fm=lm(y~X)
summary(fm))
summary(fm)
fm=lm(y~X-1)
summary(fm)
history()