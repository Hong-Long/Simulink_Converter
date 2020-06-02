# Simulink_Converter
 Record some simulation cases of electronic and electronic converters in Simulink learning process
# 目录
## Case01
  Synchronous Buck Converter
### 描述
-   . Topology:         Synchronous Buck Converter
-   . Input voltage：   30Vdc
-   . Output voltage:   15Vdc
-   . Switch frequency: 50kHz
-   . Rated power:      75W
-   . Verison:          Maltab 2016b
-   . Control method:   Single voltage close loop with a single PI controller
### Phase Shift Model No DeadTime_V1.0
### 描述
- Note:
- The model can be used to generate single-phase-shifted PWM modulated pulses where UgH1, UgL1 and UgH2, UgL2 signals are complementary, and there is a phase-shift angle Angle between UgH2 and UgH1.
- Instructions:
- Double-click the SPS Control module, the user can modify the PWM frequency according to his needs.
- The Create Phase shift angle module at the front end is used to generate the phase shift angle, and the user can customize it as needed.
### Bug
At present, this module can only realize the positive phase shift, and cannot effectively carry out the bidirectional phase shift.