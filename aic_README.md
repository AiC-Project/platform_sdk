
How to compile thes TCP render libs to aic_SDLplayer

make lib64cutils lib64OpenglRender lib64EGL_translator lib64GLES_CM_translator lib64GLES_V2_translator ; 

then push them in aic_SDLplayer/lib/.
cp out/host/linux-x86/obj/lib/lib64*.so sdl_broker_sensor/lib/.

