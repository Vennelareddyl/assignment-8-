library(readxl)
Assignment_6_dataset<-read_excel("/Users/vennelareddy/Downloads/Assignment-6-dataset.xlsx")
Assignment_6_dataset
library(plyr)
people_average <- ddply(Assignment_6_dataset, "Sex",transform.data.frame, Grade.average=mean(Grade))
people_average
write.table(people_average,"Average of people")
write.table(people_average,"Avg", sep=",")
people_i <- subset(Assignment_6_dataset,grepl("i",name))
people_i
write.table(people_i, "S_I", sep=",")
