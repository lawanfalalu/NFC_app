# Android NFC SDK

## What's NFC?

Near Field Communication (NFC) is a set of short-range wireless technologies, typically requiring a distance of 4cm or less to initiate a connection. NFC allows you to share small payloads of data between an NFC tag and an Android-powered device, or between two Android-powered devices.

Android-powered devices with NFC simultaneously support three main modes of operation:

1. Reader/writer mode, allowing the NFC device to read and/or write passive NFC tags and stickers.
2. P2P mode, allowing the NFC device to exchange data with other NFC peers; this operation mode is used by Android Beam.
3. Card emulation mode, allowing the NFC device itself to act as an NFC card. The emulated NFC card can then be accessed by an external NFC reader, such as an NFC point-of-sale terminal. <br>

https://developer.android.com/guide/topics/connectivity/nfc/index.html  <br>
https://en.wikipedia.org/wiki/Near_field_communication  <br>


## This SDK can do:

1. Tag reader/writer
(Support NfcA, NfcB, NfcF, NfcV, IsoDep, Ndef on NFC Forum Type 1, Type 2, Type 3 or Type 4 compliant tags, MifareUltralight, NfcBarcode. For MIFARE Classic tags, this would be useful: [MIFARE Classic Tool] (https://github.com/ikarus23/MifareClassicTool))
2. P2P beam
3. Card emulation


## References

**[Android NFC API](https://developer.android.com/reference/android/nfc/package-summary.html)**  <br>
**[NFC Forum Specification](http://nfc-forum.org/our-work/specifications-and-application-documents/specifications/)**  <br>
