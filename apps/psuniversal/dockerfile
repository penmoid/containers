FROM ironmansoftware/universal:latest
LABEL description="Universal - The ultimate platform for building web-based IT Tools" 

EXPOSE 5000
VOLUME ["/home/data"]
ENV Data__RepositoryPath /home/data/Repository
ENV Data__ConnectionString /home/data/database.db
ENV UniversalDashboard__AssetsFolder /home/data/UniversalDashboard 
ENV Logging__Path /home/data/logs/log.txt
ENTRYPOINT ["./Universal/Universal.Server"]