touch $2
x=$(grep -P '\d{8}' $1)
for i in $x
do
  efetch -db pubmed -id $i -format abstract >> $2
done
