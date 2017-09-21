    kubectl create configmap papertrail-config --from-file=fluent.conf=fluent.conf
    kubectl create -f fluent.yml
