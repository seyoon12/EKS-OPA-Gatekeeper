# EKS-OPA-Gatekeeper
OPA Gatekeeper를 이용해 kubernetes에 정책 기반 제어를 구현하였습니다.
EKS + Self-managed node + Gatekeeper 조합으로 **보안/자원 제약 정책**을 적용한 예제입니다.

# 실행 process
`/terraform/stacks/eks-cluster/ terraform apply`
`/terraform/stacks/self-managed-node/ terraform apply`
`ansible-playbook ansible-playbook

# 예시
### Namespace 라벨 제한
![image](https://github.com/user-attachments/assets/5e56bbeb-1d9f-4ae8-a424-12f64337d334)  

### Pod 리소스 제한
![image](https://github.com/user-attachments/assets/15cd5b87-2146-43bc-b256-e8b8a0f7b64d)  

### service 제한
![image](https://github.com/user-attachments/assets/198dbbc1-f063-4c5f-81ab-a1940f2b350c)
