# spec-physicallinks

Specification for standard mechanisms to link physical goods to digital credentials about the goods.

# Status

Raw - work has not yet started.

# Goals

The integrity of digital data is of much reduced value in cross border trade if it cannot be tied unambiguously and provably to the physical shipment of goods and be discoverable from the physical item. For example, a digitally verifiable product conformity certificate may be verified confidently but if it describes different goods than those in the shipment then it serves no useful purpose.

There are several mechanisms to link physical goods to credentials with different degrees of maturity and integrity. 

* GS1 Digital Links provide a simple but powerful mechanism to link the existing very large ecosystem of 2-d barcoded products to digital data. It is very likely that a new ISO standard will formalise the principles of GS1 Digital Link so that it can be applied to other identification schemes, especially those that, like GS1’s, are based on ISO/IEC 15459. These standards underpin the growing use of 2D symbols, including QR codes, to sit alongside and then replace the traditional 1D barcode. 
* DNA fingerprinting provides a mechanism to link bulk agricultural produce (eg grains or carcasses) to the related digital claims.
* Tamper-evident IoT sensors can read RFID identifiers on products, allowing strong links to corresponding digital claims.
* Several more advanced unique item identifier schemes based on DIDs (with associated public/private keypairs) can be linked to corresponding digital claims to prevent counterfeits.

This repository provides guidance for implementers on the use of physical product and consignment links for high integrity trade.

