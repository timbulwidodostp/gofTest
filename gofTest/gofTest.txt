# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Goodness-of-Fit Test Use gofTest (EnvStats) With (In) R Software
install.packages("EnvStats")
library("EnvStats")
# Estimation Goodness-of-Fit Test Use gofTest (EnvStats) With (In) R Software
gofTest = read.csv("https://raw.githubusercontent.com/timbulwidodostp/gofTest/main/gofTest/gofTest.csv", sep = ";")
gofTest <- gofTest(gofTest ~ 1, data = gofTest)
gofTest
# Goodness-of-Fit Test Use gofTest (EnvStats) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished