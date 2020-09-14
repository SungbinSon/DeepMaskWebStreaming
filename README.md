# DeepMaskWebStreaming  
DeepMaskWebStreaming using django, nginx-rtmp-module, mtcnn, arcface 

Koreatech CSE Graduate Project

By Sungbin Son, [Kiback Kim](https://github.com/whitepurple/)

web source from [https://askbootstrap.com/](https://github.com/whitepurple/VideoStreamingPlatform)

if you use this code in your research, please cite [the paper](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE09351471)
## Dependency
| Packages Version | Commands |
|--:|---|
| opencv 4.4.0 | ```conda install -c conda-forge opencv``` |
|ffpyplayer 4.3.1 | ```conda install -c conda-forge ffpyplayer```|
| django 3.0.3 | ```conda install -c anaconda django```|
| djangorestframework 3.11.1 | ```conda install -c conda-forge djangorestframework```|
| pytorch 1.6.0 | ```conda install pytorch torchvision cudatoolkit=10.2 -c pytorch```|
| facenet-pytorch 2.4.1 | ```pip install facenet-pytorch```|

## Server setting
- Ubuntu 18.04.4 LTS (GNU/Linux 5.4.0-42-generic x86_64)
- Install Nginx with nginx-rtmp-module [(link)](https://github.com/arut/nginx-rtmp-module) [(bash)](https://github.com/whitepurple/VideoStreamingPlatform/blob/master/install_nginx_with_rtmp_module.sh)
- 
- 



## License
MIT License
