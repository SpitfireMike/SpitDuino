SpitDuino
=========

Adding digital instrumentation and control to an old Triumph Spitfire
---------------------------------------------------------------------
1969 Triumph Spitfire MarkIII, pre-OBD, nothing more advanced than mechanically operated distributor.

Multiple parts to this:
  *   Speedometer - original speedo drive gear is stripped and replacement is not readily available
    *   Start with speed from a GPS, eventually use Hall-Effect on the driveshaft
    *   Drive analog gauge using stepper motor
    *   Add 6-digit display for tripmeter, 7mm * 250mm (about .3 * 1")
    *   Add 4-digit odometer, each digit 7mm * 4mm
  *   Tachometer
    *   Filter pulses from ignition coil (-)
    *   Pulse counter or Freq->Volt converter
    *   Drive analog gauge using stepper motor
    *   Add 4-digit digital display, same dimensions as speedometer 
  
