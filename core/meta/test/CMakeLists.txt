ROOT_ADD_GTEST(testStatusBitsChecker testStatusBitsChecker.cxx LIBRARIES Core)
ROOT_ADD_GTEST(testHashRecursiveRemove testHashRecursiveRemove.cxx LIBRARIES Core)
ROOT_ADD_GTEST(testTClass testTClass.cxx LIBRARIES Core)
configure_file(stlDictCheck.h . COPYONLY)