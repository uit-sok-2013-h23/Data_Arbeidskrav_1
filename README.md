# Data Arbeidskrav 1

# Hvordan laste inn dataen:

#Last ned nødvendig pakke

library(readr)

#Last inn data ved bruk av URL

# Datasett til Oppgave 1
url <- "https://raw.githubusercontent.com/UiT-sok-2013-h24/arbeidskrav2/5a3131437da15bf77fa821ca19fd4503b7e334cd/datasett1.csv"
data1 <- read.csv(url)

# Datasett til Oppgave 2
url <- "https://raw.githubusercontent.com/UiT-sok-2013-h24/arbeidskrav2/5a3131437da15bf77fa821ca19fd4503b7e334cd/datasett2.csv"
data2 <- read.csv(url)
