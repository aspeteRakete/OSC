### OSC Library build static
generate_arduino_library(osc_atmega328
    SRCS OSCBundle.cpp  OSCData.cpp  OSCMessage.cpp  OSCTiming.cpp  SLIPEncodedSerial.cpp  SLIPEncodedUSBSerial.cpp
    HDRS OSCBoards.h OSCBundle.h OSCData.h OSCMatch.h  OSCMessage.h  OSCTiming.h  SLIPEncodedSerial.h  SLIPEncodedUSBSerial.h
    )

generate_arduino_library(osc_mega2560
     SRCS OSCBundle.cpp  OSCData.cpp  OSCMessage.cpp  OSCTiming.cpp  SLIPEncodedSerial.cpp  SLIPEncodedUSBSerial.cpp
     HDRS OSCBoards.h OSCBundle.h OSCData.h OSCMatch.h  OSCMessage.h  OSCTiming.h  SLIPEncodedSerial.h  SLIPEncodedUSBSerial.h
     BOARD mega2560
     )

