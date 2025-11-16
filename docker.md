docker create --gpus all --net=host --shm-size="10g" --cap-add=SYS_ADMIN -v .:/workspace/verl --name verl verlai/verl:app-verl0.5-transformers4.55.4-vllm0.10.0-mcore0.13.0-te2.2 sleep infinity
  
docker start verl_siqi
  
docker exec -it verl_siqi bash
  
docker images

docker ps
