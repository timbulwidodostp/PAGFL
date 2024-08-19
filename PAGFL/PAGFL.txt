# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Joint estimation of latent groups and group-specific coefficients in panel data models Use pagfl With (In) R Software
install.packages("PAGFL")
library("PAGFL")
PAGFL = read.csv("https://raw.githubusercontent.com/timbulwidodostp/PAGFL/main/PAGFL/PAGFL.csv",sep = ";")
# Estimation Joint estimation of latent groups and group-specific coefficients in panel data models Use pagfl With (In) R Software
PAGFL <- pagfl(y ~ X1 + X2, data = PAGFL, n_periods = 150, lambda = 20)
summary(PAGFL)
# Joint estimation of latent groups and group-specific coefficients in panel data models Use pagfl With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished