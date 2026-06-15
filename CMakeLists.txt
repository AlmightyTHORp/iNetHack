cmake_minimum_required(VERSION 3.20)
project(iNethack LANGUAGES SWIFT) # Or OBJC / CXX

# Define the iOS executable target
add_executable(iNethack 
    main.swift
    AppDelegate.swift
    ViewController.swift
)
