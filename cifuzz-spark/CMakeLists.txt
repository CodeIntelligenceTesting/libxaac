#cifuzz:build-template:begin
#add_fuzz_test({{ .FuzzTestName }} {{ .FileName }})
##target_link_libraries({{ .FuzzTestName }} PRIVATE "$<LINK_LIBRARY:WHOLE_ARCHIVE,libxaacenc>")
#target_link_libraries({{ .FuzzTestName }} PRIVATE "$<LINK_LIBRARY:WHOLE_ARCHIVE,libxaacdec>")
#cifuzz:build-template:end
