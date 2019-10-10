Bootstrap: docker
From: registry.gitlab.com/rode0day/fuzzer-testing/qsym_runner:16.04

%labels
    MAINTAINER Josh Bundt
    DockerTagID cde42b7f8

%environment
    export AFL_SKIP_CPUFREQ=1
    export LC_ALL=C

%runscript
    exec /start_fuzzing "$@"

