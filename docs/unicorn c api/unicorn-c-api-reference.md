# UNICORN C API - C REFERENCE
## Constants
UNICORN_ACCELEROMETER_CHANNELS_COUNT<br/>
The number of available accelerometer channels.<br/><br/>
UNICORN_ACCELEROMETER_CONFIG_INDEX<br/>
Index of the first accelerometer UNICORN_AMPLIFIER_CHANNEL in the UNICORN_AMPLIFIER_CONFIGURATION channels array.<br/><br/>
UNICORN_BATTERY_CONFIG_INDEX<br/>
Index of the battery level UNICORN_AMPLIFIER_CHANNEL in the UNICORN_AMPLIFIER_CONFIGURATION channels array.<br/><br/>
UNICORN_COUNTER_CONFIG_INDEX<br/>
Index of the counter UNICORN_AMPLIFIER_CHANNEL in the UNICORN_AMPLIFIER_CONFIGURATION
channels array.<br/><br/>
UNICORN_DEVICE_VERSION_LENGTH_MAX<br/>
The maximum length of the Unicorn Brain Interface version.<br/><br/>
UNICORN_EEG_CHANNELS_COUNT<br/>
The number of available EEG channels. <br/><br/>
UNICORN_EEG_CONFIG_INDEX<br/>
Index of the first EEG UNICORN_AMPLIFIER_CHANNEL in the UNICORN_AMPLIFIER_CONFIGURATION channels array.<br/><br/>
UNICORN_FIRMWARE_VERSION_LENGTH_MAX<br/>
The maximum length of the firmware version. <br/><br/>
UNICORN_GYROSCOPE_CHANNELS_COUNT<br/>
The number of available gyroscope channels. <br/><br/>
UNICORN_GYROSCOPE_CONFIG_INDEX<br/>
Index of the first gyroscope UNICORN_AMPLIFIER_CHANNEL in the 
UNICORN_AMPLIFIER_CONFIGURATION channels array.<br/><br/>
UNICORN_NUMBER_OF_DIGITAL_OUTPUTS<br/>
The number of digital output channels. <br/><br/>
UNICORN_RECOMMENDED_BLUETOOTH_DEVICE_MANUFACTURER<br/>
The manufacturer of the recommended (delivered) Bluetooth adapter.<br/><br/>
UNICORN_RECOMMENDED_BLUETOOTH_DEVICE_NAME<br/>
The Unicorn Brain Interface name of the recommended (delivered) Bluetooth adapter.<br/><br/>
UNICORN_SAMPLING_RATE<br/>
The sampling rate of the Unicorn Brain Interface.<br/><br/>
UNICORN_SERIAL_LENGTH_MAX<br/>
The maximum length of the serial number.<br/><br/>
UNICORN_STRING_LENGTH_MAX<br/>
The maximum string length.<br/><br/>
UNICORN_SUPPORTED_DEVICE_VERSION<br/>
The Unicorn Brain Interface version which is valid for this API.
UNICORN_TOTAL_CHANNELS_COUNT<br/>
The total number of available channels.<br/><br/>
UNICORN_VALIDATION_CONFIG_INDEX<br/>
Index of the validation indicator UNICORN_AMPLIFIER_CHANNEL in the 
UNICORN_AMPLIFIER_CONFIGURATION channels array.<br/><br/>

## Error Codes
UNICORN_ERROR_BLUETOOTH_INIT_FAILED<br/>
The initialization of the Bluetooth adapter failed.<br/><br/>
UNICORN_ERROR_BLUETOOTH_SOCKET_FAILED<br/>
The operation could not be performed because the Bluetooth socket failed.<br/><br/>
UNICORN_ERROR_BUFFER_OVERFLOW<br/>
The acquisition buffer is full.<br/><br/>
UNICORN_ERROR_BUFFER_UNDERFLOW<br/>
The acquisition buffer is empty.<br/><br/>
UNICORN_ERROR_CONNECTION_PROBLEM<br/>
The operation could not complete because of connection problems.<br/><br/>
UNICORN_ERROR_GENERAL_ERROR<br/>
An unspecified error occurred.<br/><br/>
UNICORN_ERROR_INVALID_CONFIGURATION<br/>
The configuration is invalid.<br/><br/>
UNICORN_ERROR_INVALID_HANDLE<br/>
The specified Unicorn handle is invalid.<br/><br/>
UNICORN_ERROR_INVALID_PARAMETER<br/>
One of the specified parameters does not contain a valid value.<br/><br/>
UNICORN_ERROR_OPEN_DEVICE_FAILED<br/>
The Unicorn Brain Interface could not be opened.<br/><br/>
UNICORN_ERROR_OPERATION_NOT_ALLOWED<br/>
The operation is not allowed during acquisition or non-acquisition.<br/><br/>
UNICORN_ERROR_SUCCESS<br/>
The operation completed successfully. No error occurred.<br/><br/>
UNICORN_ERROR_UNSUPPORTED_DEVICE<br/>
The Unicorn Brain Interface is not supported with this API (UNICORN_SUPPORTED_DEVICE_VERSION).<br/><br/>

## Type Definitions
BOOL<br/>
The Boolean data type, whose values can be TRUE or FALSE.<br/><br/>
FALSE<br/>
The FALSE value for the BOOL type.<br/><br/>
TRUE<br/>
The TRUE value for the BOOL type.<br/><br/>
NULL<br/>
The null pointer.<br/><br/>
UNICORN_DEVICE_SERIAL<br/>
The type that holds Unicorn Brain Interface serial.<br/><br/>
UNICORN_DEVICE_VERSION<br/>
The type that holds Unicorn Brain Interface version.<br/><br/>
UNICORN_FIRMWARE_VERSION<br/>
The type that holds firmware version.<br/><br/>
UNICORN_HANDLE<br/>
The type that holds the Unicorn Brain Interface handle associated with a device.<br/><br/>