This Pod runs the Streamlit container from eliezer206568107/streamlit_app:latest and listens on 8080.
Run: kubectl apply -f pod.yaml
Check: kubectl get pod streamlit-pod ; kubectl logs streamlit-pod