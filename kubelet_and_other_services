for SERVICES in docker etcd kube-proxy kubelet; do
    systemctl restart $SERVICES
    systemctl enable $SERVICES
    systemctl is-active $SERVICES
done
