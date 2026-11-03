# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Regression Method for Truncated Normal Distribution with Censored Data Use tcensReg With (In) R Software
install.packages("remotes")
remotes::install_github("williazo/tcensReg")
library("tcensReg")
# Estimate Regression Method for Truncated Normal Distribution with Censored Data Use tcensReg With (In) R Software
tcensReg_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/tcensReg/main/tcensReg/tcensReg.csv",sep = ";")
tcensReg <- tcensReg(y ~ x1, data = tcensReg_r)
tcensReg_ <- tcensReg(y ~ x2, data = tcensReg_r)
summary(tcensReg)
summary(tcensReg_)
# Regression Method for Truncated Normal Distribution with Censored Data Use tcensReg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished