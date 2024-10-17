# nativejvmmetricsissue

This is a minimal reproducible of an issue I am observing


Please download this app, out of the box, after clean install and springboot:run, you will be able to see metrics here:
Especially, the metrics if type jvm_buffer_* and jvm_gc_* are PRESENT.


Now, please clean everything, and build a native image, using mvn -Pnative spring-boot:build-image
Same, please just run the docker image, no need for real traffic


Please let me know if you observe that with the native image, some metrics are missing, while metrics are present for non native image.

Thank you
