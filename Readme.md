Complete Setup Guide: Internal NLB + Envoy Gateway + Gateway API on AWS EKS (Private Network)

1. helm install eg oci://docker.io/envoyproxy/gateway-helm --version v1.8.0 -n envoy-gateway-system --create-namespace

2. Create GatewayClass (gatewayclass.yaml)

3. Create EnvoyProxy Config NLB (envoy.yaml)

4. Create Gateway (gateway.yaml)
