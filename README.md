# Undergraduate Thesis
Business Process Automation Using Business Process Management System (Case Study on the Yearly Motor Vehicle Tax Collection Process at Samsat)

Supervisor: Prof. Dr. rer. pol. Hamzah Ritchi, S.E., MBIT., Ak.

Created using [NEXTFLOW](https://nextplatform.ai/product/nextflow) by [NEXTPLATFORM](https://nextplatform.ai/)

## Demo

[![Demo](http://img.youtube.com/vi/CnG7P4coPq8/0.jpg)](http://www.youtube.com/watch?v=CnG7P4coPq8)

## Business Process Model and Notation (BPMN)
### As-Is
![As-Is](img/bpmn/01-as-is.svg)

### To-Be
![As-Is](img/bpmn/02-to-be.svg)

### Implementation
![As-Is](img/bpmn/03-implementation.svg)

[Source Code](src/bpmn/)

## Decision Model and Notation (DMN)
### Pengenaan
![Pengenaan](img/dmn/pengenaan.png)

### NJKB
![NJKB](img/dmn/njkb.png)

### Bobot
![Bobot](img/dmn/bobot.png)

### Tarif
![Tarif](img/dmn/tarif.png)

### SWDKLLJ
![Tarif](img/dmn/swdkllj.png)

[Source Code](src/dmn/)

## Forms
### Initiation
![Initiation](img/form/00%20-%20Initiation.png)

### Registration
![Registration](img/form/01%20-%20Registration.png)

### Review NPPKB - PKB
![Review NPPKB - PKB](img/form/02a%20-%20Review%20NPPKB%20-%20PKB.png)

### Review NPPKB - SWDKLLJ
![Review NPPKB - SWDKLLJ](img/form/02b%20-%20Review%20NPPKB%20-%20SWDKLLJ.png)

### Revise NPPKB - PKB
![Review NPPKB - PKB](img/form/03a%20-%20Revise%20NPPKB%20-%20PKB.png)

### Revise NPPKB - SWDKLLJ
![Review NPPKB - SWDKLLJ](img/form/03b%20-%20Revise%20NPPKB%20-%20SWDKLLJ.png)

### Approval for System Override
![Approval for System Override](img/form/04a%20-%20Approval%20for%20System%20Override.png)

### Show NPPKB
![Show NPPKB](img/form/05%20-%20Show%20NPPKB.png)

### Payment Confirmation
![Show NPPKB](img/form/06%20-%20Payment%20Confirmation.png)

### Show SKKP
![Show SKKP](img/form/07%20-%20Show%20SKKP.png)

[Source Code](src/form/)

## Test Case
### Permendagri No. 1 Tahun 2021 Pasal 9(1)
![Permendagri No. 1 Tahun 2021 Pasal 9(1)](test/Permendagri%20No.%201%20Tahun%202021%20Pasal%209(1).png)

### Permendagri No. 1 Tahun 2021 Pasal 9(3)
![Permendagri No. 1 Tahun 2021 Pasal 9(3)](test/Permendagri%20No.%201%20Tahun%202021%20Pasal%209(3).png)

### Permendagri No. 1 Tahun 2021 Pasal 10(1)
![Permendagri No. 1 Tahun 2021 Pasal 10(1)](test/Permendagri%20No.%201%20Tahun%202021%20Pasal%2010(1).png)

### Permendagri No. 1 Tahun 2021 Pasal 11(1)
![Permendagri No. 1 Tahun 2021 Pasal 11(1)](test/Permendagri%20No.%201%20Tahun%202021%20Pasal%2011(1).png)

### Permendagri No. 1 Tahun 2021 Pasal 12(1)
![Permendagri No. 1 Tahun 2021 Pasal 12(1)](test/Permendagri%20No.%201%20Tahun%202021%20Pasal%2012(1).png)

Notes: 
- UU Nomor 1 Tahun 2022 Pasal 10(1), UU Nomor 1 Tahun 2022 Pasal 10(3) & UU Nomor 1 Tahun 2022 Pasal 7(2) is indirectly tested with cases above.
- Process Variable with `null` or `0` value will be shown as empty.
