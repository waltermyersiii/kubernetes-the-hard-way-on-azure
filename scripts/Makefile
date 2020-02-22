ssh-controller-0:
        ssh kuberoot@$(shell az network public-ip show -g kubernetes -n controller-0-pip --query "ipAddress" -otsv)

ssh-controller-1:
        ssh kuberoot@$(shell az network public-ip show -g kubernetes -n controller-1-pip --query "ipAddress" -otsv)

ssh-worker-0:
        ssh kuberoot@$(shell az network public-ip show -g kubernetes -n worker-0-pip --query "ipAddress" -otsv)

ssh-worker-1:
        ssh kuberoot@$(shell az network public-ip show -g kubernetes -n worker-1-pip --query "ipAddress" -otsv)