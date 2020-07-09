At least MAX 8 reqired.
This patch transforms audio into matrix with an fft.
You get the "frequencys" of the fft into matrix format. 
With jit.gen you can transform this values into 3d images. 
It is reccomended to use jitter effects (jit.rota,jit.slide....) and to convert the signal back into audio.
The result is interesting. 




1. Load audio file(s) into playlist.
2. activate dac.
(check dimensions and fps of jit.world)

Optional:
Transform with ifft patch the matrix into sound.
Change qmetro speed. 
Render video!
