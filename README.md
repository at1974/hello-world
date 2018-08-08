# hello-world
repositorio teste
# teste 123 #
ggplot(data = pf, aes(x = dob_day)) + 
   geom_histogram(binwidth = 1) + 
   scale_x_continuous(breaks = 1:31) + 
   facet_wrap(~dob_month)
