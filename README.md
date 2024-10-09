# Istio-ServiceMesh
Istio-ServiceMesh documentation

What is service mesh?

What is Istio?

Why is Istio needed?


How does Istio work?


istiod
istio Citadel
istio Galley
istio envoy proxy
envoy proxy

admission controller (Dynamic adminission control) --> mutate/validate
istio enable sidecar injection:
kubectl label namespace/default isito_injection=enabled.

virtual service

destination rules

permissive vs strict

storage class admission controller

available admission controllers

egress and ingress gateway

mutating admission webhook controller and validating admission webhook controller
North-South traffic: refers to network traffic that enters or exits an organization's internal network.
East-West traffic: traffic that occurs within the network.
