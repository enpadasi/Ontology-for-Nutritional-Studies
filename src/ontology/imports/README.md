curl -s -F file=@imports/general_ontofox.txt -o general_import.owl https://ontofox.hegroup.org/service.php
robot reduce --input general_import.owl --xml-entities --prefix "obo: http://purl.obolibrary.org/obo/" --reasoner ELK --output imports/general_import.ofn
