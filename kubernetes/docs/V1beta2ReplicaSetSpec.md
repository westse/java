
# V1beta2ReplicaSetSpec

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**minReadySeconds** | **Integer** | Minimum number of seconds for which a newly created pod should be ready without any of its container crashing, for it to be considered available. Defaults to 0 (pod will be considered available as soon as it is ready) |  [optional]
**replicas** | **Integer** | Replicas is the number of desired replicas. This is a pointer to distinguish between explicit zero and unspecified. Defaults to 1. More info: https://kubernetes.io/docs/concepts/workloads/controllers/replicationcontroller/#what-is-a-replicationcontroller |  [optional]
**selector** | [**V1LabelSelector**](V1LabelSelector.md) | Selector is a label query over pods that should match the replica count. If the selector is empty, it is defaulted to the labels present on the pod template. Label keys and values that must match in order to be controlled by this replica set. More info: https://kubernetes.io/docs/concepts/overview/working-with-objects/labels/#label-selectors |  [optional]
**template** | [**V1PodTemplateSpec**](V1PodTemplateSpec.md) | Template is the object that describes the pod that will be created if insufficient replicas are detected. More info: https://kubernetes.io/docs/concepts/workloads/controllers/replicationcontroller#pod-template |  [optional]



