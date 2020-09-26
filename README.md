# K8s_Namespace
Kubernetes 叢集資源的分配集合群組『命名空間』


命名空間是 K8s 一重要概念，將系統內部物件（包含豌豆莢子、副本控制器、節點服務群）分配到不同的命名空間，成為邏輯群組，使不同群組（命名空間）共用整個叢集資源。

K8s 叢集利用 kubectl 工具建立命名空間。

* 建立指令

      #kubectl get namespaces

* 查詢指令

      #kubectl get namespaces


* 加入參數

      #kubectl get pods --namespace=[命名空間名稱]

