## datasets
1. This dataset was collected at SAS 2016 in Catania, Italy.  As noted in the files, they contain accelerometer, gyroscope, and magnetometer data.   
2. They were collected by the conference partipants using multiple mobile devices (smart phones), supervised by Yanyan Zhuang, Seth Miller and Richard Weiss.
3. The units of measurement are:

ax, ay, az - m/s/s

gx, gy, gz - rad/s

mx, my, mz - uT (micro-Tesla)

4. The height of each user is included with the sensor data for that user.
5. Since data was received asynchronously for each sensor, each line will typically only contain data for one sensor, so the others will be blank.
6. Several fiducial points were chosen, and their relative locations were measured using a laser range finder.
7. When a user arrived at one of these points, the phone was placed in a specified orientation, where the y-axis was pointing up, the x-axis was horizontal and parallel to the wall.
