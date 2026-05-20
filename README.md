# talaria-komodo
Stuff for the Talaria Komodo, duh.

## DBC
Some notes regarding the DBC:
 - Most of the major signals should be correct (SOC, Voltage, Current)
 - Any signal with "probably" or "maybe" are just wild guesses
 - Also any temperature value currently seem implausible, there may be some offset or different unit/scaling
 - Note that 0x009 - 0x00C are not actually present on the CAN, they are a crutch to allow for better visual representation in SavvyCan when the multiplexed 0x008 message is split into their own messages (0x008+1+mux_id)

The CAN in the Komodo is running at 250 kbit/s.

If you use the DBC and find a new signal or improvement for existing ones let me know or generate a pull request so everybody can benefit from it.
