# jfr-monitoring
Quick Example to monitor with JFR (and visualize with JMC)


TODO : 

Sample app (with some issues ?)

How to use JFR : 

- Java 11+ :

  `java -XX:StartFlightRecording=<opts> path-to-class-file`

  `java -XX:StartFlightRecording=<opts> -jar xx.jar `

- Java < 11 : 

  Need to add `-XX:+UnlockCommercialFeatures -XX:+FlightRecorder`

How to Visualize : 
- JMC

Source: 

https://www.youtube.com/watch?v=plYESjZ12hM

https://www.youtube.com/watch?v=m9lzneJaHYI (FR)

https://www.baeldung.com/java-flight-recorder-monitoring

See also : 

- Profilers : 

  Honest Profiler : https://github.com/jvm-profiling-tools/honest-profiler/wiki/How-to-Run

  async-profiler : https://github.com/jvm-profiling-tools/async-profiler/wiki

- Visualize : 

  VisualVM : https://visualvm.github.io/
