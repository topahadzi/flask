# flask

# Build Docker Image
docker build -t flask .

# Check Docker Image
docker images

# Running Docker Image
docker run -d --name flask -p 5000:5000 flask


