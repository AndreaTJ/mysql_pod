Run 


  kubectl apply -f mysql-secret.yaml 
  kubectl apply -f mysql.yaml
  kubectl exec -it mysqla sh
  # mysql -p[password]
  kubectl delete pod mysqla

