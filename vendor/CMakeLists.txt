include(FetchContent)

FetchContent_Declare(ValveFileVDF SYSTEM
    GIT_REPOSITORY
    "https://github.com/TinyTinni/ValveFileVDF"
    GIT_TAG
    "2d4c60eb160bc413ef4bafb0c1fd5ccf92ae4705"
)
FetchContent_MakeAvailable(ValveFileVDF)

FetchContent_Declare(argparse SYSTEM
    GIT_REPOSITORY
    "https://github.com/p-ranav/argparse"
    GIT_TAG
    "v3.1"
)
FetchContent_MakeAvailable(argparse)

FetchContent_Declare(GTest SYSTEM
    GIT_REPOSITORY
    "https://github.com/google/googletest"
    GIT_TAG
    "v1.15.0"
)
FetchContent_MakeAvailable(GTest)

FetchContent_Declare(abseil SYSTEM
    GIT_REPOSITORY
    "https://github.com/abseil/abseil-cpp"
    GIT_TAG
    "20240722.0"
)
FetchContent_MakeAvailable(abseil)
