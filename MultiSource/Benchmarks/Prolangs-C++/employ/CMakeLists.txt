set(RUN_OPTIONS 400 < input.txt)
set(HASH_PROGRAM_OUTPUT 1)
llvm_multisource(employ)
llvm_test_data(employ input.txt)
