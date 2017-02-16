## Bluetooth Details

While all lovense toys use the same protocol, they communicate over
bluetooth differently, depending on when they were released.

When discovering or pairing with Lovense toys, toys identify using the
format "LVS-?001". The ? will be a letter pertaining to
the [model specifier](models.md). For instance, when discovering the
Hush Buttplug, it will show up as "LVS-Z001".

### Bluetooth 2.0 Toys

The first toys released by Lovense used Bluetooth 2.0 SPP, emulating a
serial port connection. 

These toys include:

- Max
- Nora
- Lush

When paired with a system, these toys identify

### Bluetooth LE Toys

Starting with the Hush, all toys released by Lovense use Bluetooth LE.

These toys include:

- Hush
- Edge
- Ambi
- Osci
- Domi

These toys have GATT characteristics to mimic the RX/TX setup of the
serial port style control of the old toys.

Service UUID (Hush):
```
6e400001-b5a3-f393-e0a9-e50e24dcca9e
```

TX Characteristic UUID (Hush):
```
6e400002-b5a3-f393-e0a9-e50e24dcca9e
```

RX Characteristic UUID (Hush): 
```
6e400003-b5a3-f393-e0a9-e50e24dcca9e
```
