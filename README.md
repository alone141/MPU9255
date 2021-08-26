# MPU9255
MPU9255 library for STM32 microcontrollers using I2C and HAL libraries. Will add more features in the future.

# Functions

**MPU9255_Init(I2C_HandleTypeDef);**

Initializes the MPU by passing the I2C channel to the library, confirms the device ID and sets the registers to the required values.  

**MPU9255_Accel_Raw(MPU_DataStruct);  **

Gets raw acceleration values and stores them as an integer in the Ax_RAW, Ay_RAW and Az_RAW variables of a MPU_DataStruct data type.

**MPU9255_Accel_Scaled(MPU_DataStruct ); **

Gets scaled acceleration values and stores them as a double in the Ax, Ay and Az variables of a MPU_DataStruct data type.

**MPU9255_Gyro_Raw(MPU_DataStruct );  **

//  Gets raw gyroscope values and stores them as an integer in the Gx_RAW, Gy_RAW and Gz_RAW variables of a MPU_DataStruct data type.

**MPU9255_Gyro_Scaled(MPU_DataStruct );  **

// Gets scaled gyroscope values and stores them as a double in the Gx, Gy and Gz variables of a MPU_DataStruct data type.

**MPU9255_Angle(MPU_DataStruct); **

//Gets the pitch and roll angles and stores them as a double in the roll and pitch variables of a MPU_DataStruct data type.

**MPU_READ_ALL(MPU_DataStruct); **

// Stores all values in the MPU_DataStruct.

