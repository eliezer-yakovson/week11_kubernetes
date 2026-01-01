This service exposes the application and creates a DNS service to route traffic to pods marked app=streamlit-app on port 8080.
Run: kubectl apply -f service.yaml
Test: kubectl get svc streamlit-service 
