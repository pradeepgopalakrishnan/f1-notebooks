# f1-notebooks

## Ideas:
- $$laptime = t_{drs/slipstream} + f(c_{tyre age}, c_{tyre compound}) + c_{car} +\epsilon_{residual error}$$
  * the tyre age/compound term might as well be a limear function of the constants
  * estimate $c_{car}$ over the race/season, should be an interesting analysis
- Lap level position volatility for drivers
- Front and rear wing image analysis? from Twitter (albert.fabrega)
- Tyre deg analysis: [link0](https://www.reddit.com/r/F1Technical/comments/11oskuy/computation_of_fuelcorrected_lap_time/) [link1](https://www.reddit.com/r/F1Technical/comments/wrdmmt/hungarian_gp_heat_map_of_fuel_corrected_lap_times/) [link2](https://www.reddit.com/r/F1Technical/comments/y66r32/how_is_tyre_degradation_measured/) [link3](https://www.mdpi.com/2076-3417/10/12/4229)
  * conventional methods: start fuel load  = 110 kg, end fuel load = 1 kg, 1 kg => 30-35 ms laptime. assume uniform fuel depletion and subtract 0.035*fuel left from laptime for fuel corrected laptime
  * problems: everyone starts with 110 kg always? uniform fuel depletion(laptime independent of mass of car + fuel left at time t)? DRS/dirty air/traffic effects?
  * Optimal trye change pt: "What I’ve heard from a former F1 engineer, is that they measure the difference between external wall and internal wall temperature of the tyres. In the Friday tests, they establish the acceptable threshold and take a decision from that point."
- Track evolution: [link0](https://buildingspeed.org/2016/08/05/how-tracks-take-and-lose-rubber/)
  * James Vowles gives a pretty thorough explanation when asked in Q1. The fastest time is normally the first lap on a fresh set of tyres, with the track also ramping up in speed. So the second run on a used set may actually match or beat the first run. But go again on new, and it should be a lot faster. He mentioned that there was a support race (F3 seems to ring a bell), and the rubber is a lot different to the F1 rubber as the mechanics of the tyre are different he said. So that removes the F1 rubber that was laid into the track in the FP sessions, and essentially turns it into a green track. F1 rubber grips best to f1 rubber- so the first runs in Q1 were blowing any dust and debris off the track, and laying down new F1 rubber into the surface. By the second run, the track was grippier and the lap times fell.
- Track deg analysis:
  
