cmake_minimum_required(VERSION 3.20)
project(Anomaly_Detector)

set(CMAKE_CXX_STANDARD 11)

add_executable(Anomaly_Detector
        AnomalyDetector.h
        CLI.h
        CLI.cpp
        HybridAnomalyDetector.h
        HybridAnomalyDetector.cpp
        Server.cpp
        Server.h
        SimpleAnomalyDetector.h
        SimpleAnomalyDetector.cpp
        anomaly_detection_util.cpp
        anomaly_detection_util.h
        commands.h
        minCircle.h
        minCircle.cpp
        timeseries.h
        timeseries.cpp)
