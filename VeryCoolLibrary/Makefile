SWIFT_COMPILER=/usr/bin/swiftc
SDK := $(shell xcrun --sdk iphoneos --show-sdk-path)
TARGET = "arm64-apple-ios13.6"

VeryCoolLibrary:
	# Compilar VeryCoolLibrary
	$(SWIFT_COMPILER) VeryCoolLibrary.swift \
	-sdk $(SDK) \
	-target $(TARGET) \
	-emit-library \
	-static \
	-emit-module \
	-module-name $@