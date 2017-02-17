## Bluetooth Details

While all lovense toys use the same protocol, they can communicate
over bluetooth differently, depending on when they were released.

When discovering or pairing with Lovense toys, toys identify using the
format "LVS-?001". The ? will be a letter pertaining to
the [model specifier](models.md). For instance, when discovering the
Hush Buttplug, it will show up as "LVS-Z001", as "Z" is the model code
for the Hush.

### Bluetooth 2.0 Toys

The first toys released by Lovense used both Bluetooth 2.0 SPP
(emulating a serial port) and Bluetooth LE. This was most likely due
to the sparse mobile support of BTLE when they were released.

These toys include:

- Max
- Nora

When paired with a system via Bluetooth 2.0, these toys identify as a
serial port. These toys are also capable of using Bluetooth 4.0, as
outlined in the next section.

### Bluetooth LE Toys

Starting with the Lush, all toys released by Lovense use only
Bluetooth LE.

These toys include:

- Lush
- Hush
- Edge
- Ambi
- Osci
- Domi

These toys have GATT characteristics to mimic the RX/TX setup of the
serial port style control of the old toys. The GATT service and
characteristic IDs differ between the Max/Nora and all toys released
afterward.

Service UUID (Max/Nora):
```
0000fff0-0000-1000-8000-00805f9b34fb
```

TX Characteristic UUID (Max/Nora):
```
0000fff1-0000-1000-8000-00805f9b34fb
```

TX Characteristic UUID (Max/Nora):
```
0000fff2-0000-1000-8000-00805f9b34fb
```

Service UUID (All Others):
```
6e400001-b5a3-f393-e0a9-e50e24dcca9e
```

TX Characteristic UUID (All Others):
```
6e400002-b5a3-f393-e0a9-e50e24dcca9e
```

RX Characteristic UUID (All Others): 
```
6e400003-b5a3-f393-e0a9-e50e24dcca9e
```
