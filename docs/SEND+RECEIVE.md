# Send / Recieve signals

## play

Global play signal - also sends [s reset]. Similar to MIDI signal 250.

## continue

Similar to [play] - does not send [s reset]. Similar to MIDI signal 251.

## stop

Global stop signal. Does not reset (because MIDI signal stop (252) also does not reset).

## reset

Global reset signal for playback (not for resetting data)

## tick

Global ticks (16th notes atm with metro_clock)

## clock

Global clock signal (16th note / 24 afaik)

## bpm

Global BPM

