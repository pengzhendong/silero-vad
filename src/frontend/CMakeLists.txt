add_library(frontend STATIC denoiser.cc resampler.cc sample_queue.cc)
target_link_libraries(frontend PUBLIC glog samplerate RnNoise)
