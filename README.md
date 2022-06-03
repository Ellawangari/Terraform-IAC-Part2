# Terraform-IAC-Part2

#install terraform Graph

sudo apt install graphviz
# Commands to generate dependency graph
terraform graph -type=plan | dot -Tpng > graph.png
terraform graph | dot -Tpng > graph.png