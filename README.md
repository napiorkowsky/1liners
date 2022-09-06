# 1liners
1liners

cat NSRLFile.txt | awk -F "," '{print $2}' | sed 's/\"//g' | sort | uniq > NSRLFile.hash
