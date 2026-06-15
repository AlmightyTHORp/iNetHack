cmake_minimum_required(VERSION 3.20)
project(iNethack LANGUAGES SWIFT) # Or OBJC / CXX

# Define the iOS executable target
add_executable(iNethack 
    main.swift
    AppDelegate.swift
    ViewController.swift
)

# Tell CMake to target Xcode's build system structure
set_target_properties(MyAppName PROPERTIES
    XCODE_ATTRIBUTE_SDKROOT "iphoneos"
    XCODE_ATTRIBUTE_SUPPORTED_PLATFORMS "iphoneos iphonesimulator"
)
