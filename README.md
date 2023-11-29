# sdcafiine_build_env

## pull docker images
docker pull shimmer007/sdcafiine_build_env

## make 
docker run -it --rm -v .:/project shimmer007/sdcafiine_build_env make

## make clean
docker run -it --rm -v .:/project shimmer007/sdcafiine_build_env make clean

