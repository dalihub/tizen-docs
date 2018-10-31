# Tizen IoT

Tizen is commercialized for smart TV, smart phone, smart watch, and smart home appliances with three profiles: TV, mobile, and wearable. Tizen IoT Headed and Headless binary support any type of special-purpose IoT devices based on the Linux kernel. Tizen IoT Extension SDK supports for the developers to develop an application running on the Tizen IoT Headed and Headless binary. Also, using Tizen IoT extension SDK, the developers can develop the IoT devices which are connected easily and securely with legacy IoT ecosystems such as SmartThings&trade;. 

Tizen IoT Extension SDK version 1.0 is released from Tizen Studio 3.0 for Tizen 5.0. The following features are supported:

-   Hardware targets: ARTIK 530 and ARTIK 530s are supported as the official reference hardwares.Raspberry Pi 3 is also supported

-   Platform image
    -   Headless: Tizen 5.0 platform image for headless-type IoT devices without a display. Raspberry Pi 3, ARTIK 530, and ARTIK 530s can be used with the headless platform image.

    -   Headed: Tizen 5.0 platform image for headed-type IoT devices with a display. ARTIK 530 and ARTIK 530s can be used with the headed platform image.

-   Development environment

    -   IoT Setup Manager: The IoT Setup Manager is a computer application for easily setting up Tizen IoT on hardware targets. Both Linux and Windows computer environments are supported. 

    -   Tizen Studio 3.0 (or higher) is used as the IDE for developing IoT applications with the Tizen IoT Platform on Raspberry Pi 3, ARTIK 530, and ARTIK 530s.

    -   [IoT API](../guides/iot-api.md)
        -   Things SDK for SmartThings&trade;: Using Things SDK API for [SmartThings&trade;](https://smartthings.developer.samsung.com/), you can create your IoT devices with the SmartThings Cloud. The Things SDK API enables you to integrate, control, and monitor your IoT devices through the SmartThings Cloud with the SmartThings application. 

        > **Note**
        >
        > that the API set for Tizen IoT Extension SDK version 1 for Tizne 5.0 is not compatable to the API set for Tizen IoT Preview 2 for Tizen 4.0.

        -   Peripheral I/O: Using the Tizen Peripheral I/O Native API for IoT devices, you can control peripherals, such as sensors and actuators, using industry-standard protocols and interfaces.

    -   [Craftroom](https://craftroom.tizen.org/) is not supported for Tizen 5.0.

Tizen IoT Preview 2, which was released from Tizen Studio 2.0, was also supported in Tizen Studio 3.0. The following features are supported:

-   Hardware targets: Raspberry Pi 3, ARTIK 530, and ARTIK 530s are supported as reference hardware.

-   Platform image
    -   Headless: Tizen 4.0 platform image for headless-type IoT devices without a display. Raspberry Pi 3, ARTIK 530, and ARTIK 530s can be used with the headless platform image.

    -   Headed: Tizen 4.0 platform image for headed-type IoT devices with a display. ARTIK 530 and ARTIK 530s can be used with the headed platform image.

-   Development environment

    -   IoT Setup Manager: Same as Tizen IoT Extension SDK version 1.0.

    -   Tizen Studio 2.0 (or higher) is used as the IDE for developing IoT applications with the Tizen IoT Platform on Raspberry Pi 3, ARTIK 530, and ARTIK 530s.

    -   [IoT API](../guides/iot-api.md)
        -  Things SDK for SmartThings&trade;: Using Things SDK API for [SmartThings&trade;](https://smartthings.developer.samsung.com/), you can create your IoT devices with the SmartThings Cloud. The Things SDK API enables you to integrate, control, and monitor your IoT devices through the SmartThings Cloud with the SmartThings application. 

        > **Note**
        >
        > that the API set for Tizen IoT Extension SDK version 1 for Tizne 5.0 is not compatable to the API set for Tizen IoT Preview 2 for Tizen 4.0.

        -   Peripheral I/O: Same as Tizen IoT Extension SDK version 1.0.

    -   [Craftroom](https://craftroom.tizen.org/): Craftroom is a new website for creating your own development community using a Tizen platform image. Craftroom can generate a new platform image by adding IoT applications made in Tizen Studio. It provides a new functionality by combining Tizen packages, and allows you to create a new customized Tizen platform image for IoT devices in the next platform release.
        -   [Customized Platform Guide](../customized-platform/overview.md): This feature is supported only for Tizen 4.0. This feature helps the developers to create a customized platform image and selectively aggregate features and set of Tizen platform APIs.



    To get started with developing your own Tizen IoT applications:

    1.  [Setup the board](setting-up-board.md).
    2.  [Develop an application](things-app-development-5.0.md).
    3.  [Set up the SmartThings Cloud](things-cloud-setup.md).
    4.  [Test the application with SmartThings app](cloud-app-test.md).

-   [Samples](../sample/iot-sample.md): Currently only the network audio sample application is supported. The number of online samples is set to extend in the future.

