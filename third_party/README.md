third party lib version and download url
- nghttp2:
    - version: v1.40.0
    - download: https://github.com/nghttp2/nghttp2/archive/v1.40.0.tar.gz
    - change log
        - generate lib/includes/nghttp2/nghttp2ver.h
        - fix gcc8 compile warings
- protobuf:
    - version: v3.5.1
    - download: https://github.com/protocolbuffers/protobuf/archive/v3.5.1.tar.gz
- yaml-cpp:
    - version: 0.3.0
    - download: https://github.com/jbeder/yaml-cpp/archive/release-0.3.0.tar.gz
    - change log
        - rename namespace YAML to YAML_0_3
        - fix gcc8 compile warings
- re2:
    - version: 2016-02-01
    - download: https://github.com/google/re2/archive/2016-02-01.tar.gz
    - change log:
        - rename BUILD to BUILD.bak
        - fix gcc8 compile warings 
- murmurhash
    - download: https://github.com/aappleby/smhasher.git
    - change log:
        - fix gcc8 compile warings 
- googletest:
    - version: v1.8.1
    - git clone: https://github.com/google/googletest.git
- benchmark:
    - version: v1.5.0
    - git clone: https://github.com/google/benchmark.git