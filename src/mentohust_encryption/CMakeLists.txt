AUX_SOURCE_DIRECTORY("." MENTOHUST_ENCRYPTION_SRCS)
SET(EXECUTABLE_OUTPUT_PATH "${PROJECT_BINARY_DIR}/bin")
SET(LIBRARY_OUTPUT_PATH "${PROJECT_BINARY_DIR}/lib")
ADD_LIBRARY("mentohust_encryption" ${MENTOHUST_ENCRYPTION_SRCS})