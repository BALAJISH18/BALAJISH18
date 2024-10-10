apiVersion: v1
kind: PersistentVolumeClaim
metadata:
  name: wp-pv-claim
  labels:
    app: wordpress
spec:
  accessModes:
  - ReadWriteOnce
  resources:
    requests:
      storage: 20Gi
