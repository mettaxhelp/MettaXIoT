# MettaXIoT

# Solution
This document is intended to introduce the technical solutions and implementation modes of MettaxIOT. By reading this document, users can quickly grasp the capabilities and services offered by MettaxIOT. Through the document, users can swiftly deploy MettaxIOT's gateway, API, and streaming services. Users will be able to implement device data reporting, audio and video data streaming push and pull, as well as file, image, and video uploads.
# 1、Intended Audience
本文档旨在供软件开发人员、测试工程师和 FAE 阅读。

# 2、Terms

| Terms        | Description                                                            |
|--------------|------------------------------------------------------------------------|
| JT/T 808     | Communication protocol release by Ministry of Transport of China       |
| JT/T 1078    | Video communication protocol release by Ministry of Transport of China |
| MV208        |                                                                        |
| MX01         |                                                                        |
| NM           |                                                                        |
| S168         |                                                                        |
| TJSATL       |                                                                        |
| F3           |                                                                        |
| regist       | Device Initial Online                                                  |
| heart        | Device Heartbeat                                                       |
| alarm        | Device Sends Alarms                                                    |
| gps/wifi/lbs | Device Transmits GPS/WIFI/LBS Location Information                     |
| fence        | Change in Device-Fence Relationship                                    |
| notice       | Device Event Alerts                                                    |
| trip         | Vehicle Trip Calculation and Analysis                                  |
| command      | Device Online&Offline  Commands                                        |
| Web          | Accessing via the web                                                  |
| APP          | Accessing via the app                                                  |
| H5           | Offering H5 Access                                                          |
| API          | Providing API Invocation Interface                                                             |
| PUSH         |Pushing location and alarm data to other systems                                                   |
| FLEET         | Expandable Business Module - Fleet Management                                                         |
| DEVELOPER         | Expandable Business Module - Developers                                                           |


# 3、Architecture



