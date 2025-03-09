# Checklist

## Schematic design

- [x] Setup
    - [x] Set grid
    - [x] Page settings (TODO revise date on date of release)
- [x] Symbols
    - [x] Add symbols to the sheet
    - [x] Create symbols if needed
    - [x] Add values to symbols (Component values)
- [x] Arrange, annotate, associate
    - [x] Arrange symbols in functional blocks
    - [x] Annotate symbols
    - [ ] Associate with footprints
- [x] Wire
    - [x] Signals
    - [ ] Power (PWR_FLAG)
- [ ] Nets
    - [ ] Set net names
- [ ] Electrical Rules Check
    - [ ] Run ERC
    - [ ] Fix errors
    - [ ] Repeat ERC
- [ ] Comments
    - [ ] Add text information (group component in boxes, add comments)
    - [ ] Add graphics

## Layout design

- [ ] Setup
    - [ ] Set grid
    - [ ] Set design rules (check manufacturer for constraints for minimum values)
    - [ ] Import footprints from schematic
- [ ] Outline and constrains
    - [ ] Define size and shape (Edge.Cuts layer)
    - [ ] Define mounting holes
    - [ ] Define cutouts
- [ ] Footprints
    - [ ] Place components on board
    - [ ] Arrange user interface components
    - [ ] Arrange in functional blocks
    - [ ] Complete placement
- [ ] Route
    - [ ] Critical traces
    - [ ] Power
    - [ ] Copper fills
    - [ ] Everything else
- [ ] Silkscreen (F.Silkscreen and B.Silkscreen layers)
    - [ ] Add text information (reference designators, functionality text (boost, gain, bright...))
    - [ ] Add graphics (name, personal logo/name, version)
- [ ] Design rules check
    - [ ] Run DRC
    - [ ] Fix errors
    - [ ] Repeat DRC
- [ ] Export & Manufacture
    - [ ] Create Gerber files
    - [ ] Verify Gerber files
    - [ ] Upload Gerber files to manufacturer