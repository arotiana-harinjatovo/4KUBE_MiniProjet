# 4KUBE_MiniProjet
## Maîtriser les infrastructures Cloud-Native avec Kubernetes avec *kubeadm*
**Pré-requis**
    - minimum 2 GB RAM par machine 
    - 2 processeurs ou plus
    - Connectivité réseau complète entre toutes les machines du cluster (réseau public ou privé)
    - Certains ports doivent êtres ouverts sur vos machines. Voir ici pour plus de détails
    - Swap impérativement désactivé pour pouvoir utiliser kubelet

**Introduction**
Dans un cluster Kubernetes, nous allons avoir deux catégories de noeuds (VM). 

Noeud Master : pour le plan management.
Noeuds Worker : pour le plan assitance et le management des ressources.

## Configuration d'un cluster sur Ubuntu
### 1. Machines Virtelles (VM) sur VMWare
  Création d'une machine virtuelle (master)  et de 2 machines virtuelles (worker1/worker2)
    - configuration des nom d'hôte de chaque machine
    [hostnamectl set-hostname <nom-hôte>] *# Lancer avec le terminal*
    
  Avant toutes installations, il est nécessaire que dans le cluster peuvent   
  
  


