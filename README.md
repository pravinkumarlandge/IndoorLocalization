# Indoor-Localisation-for-Context-Aware-Application
Indoor localisation to permit a user device to gain access to a service provided by an IoT device. Linear SVM model trained on data from various sensors is used on devices acting as service providers. Devices acting as users transmit connectivity data to service device and data is run through SVM model. System is based on the oneM2M framework and uses MongoDB as a means of storing data.

LoPys and a Raspberry Pi were placed at various location within the SMART infrastructure at the University of Wollongong. The Python code given in this repository shows how the connectivity data of all devices is obtained and communicated to a infrastructure node (IN) instance on an OM2M server. The connecivity data is gathered at 30 second intervals and the statistical data of each device is used for the training of SVM classifier models for each service provder device.
