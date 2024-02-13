# CHI-KNOW-PO
HTR ground-truth of the CHI-KNOW-PO project.

The CHI-KNOW-PO project aims to digitize a corpus of poetic anthologies, commentaries, dictionaries and encyclopedias from the Chinese medieval period (ca. 200-1000) and process them using HTR.

[Official page of the project](https://www.collexpersee.eu/projet/chi-know-po-corpus/)

## Dataset composition

To date, dataset contains 306 images, for a total of:

* 1.175 TextRegions
* 12.198 TextLines
* 97.523 Glyphs

## Images

TBD

## Ground-truth specifications

TBD

### Informations levels

We provide for each image a pageXML file containing three level of information:
* TextRegion localisation, with a semantic tag (e.g. `MainText`), following the [SegmOnto ontology](https://github.com/SegmOnto/Guidelines);
* Baseline localisation and surrounding polygon of the line. Each baseline contains a semantic tag;
* Text.

```xml
    <TextRegion id="79718" custom="structure {type:MainText;}">
      <Coords points="2575,4313 2575,2861 2563,1405 219,1413 216,4307 2575,4313"/>
      <TextLine id="870481" custom="structure {type:Text;}">
        <Coords points="2491,1414 2414,1414 2414,1515 2392,1534 2411,1584 2392,1627 2411,1679 2397,1732 2414,1751 2397,2082 2417,2102 2400,2178 2419,2206 2400,2258 2425,2338 2571,2352 2559,1411 2491,1414"/>
        <Baseline points="2492,1415 2504,2327"/>
        <TextEquiv>
          <Unicode>見惡焉其終也已</Unicode>
        </TextEquiv>
      </TextLine>
      <TextLine id="870482" custom="structure {type:Commentary;}">
        <Coords points="2535,2356 2488,2356 2477,2395 2493,2507 2474,2545 2493,2595 2474,2732 2491,2822 2477,2852 2493,2998 2480,3025 2493,3132 2482,3250 2502,3266 2641,3258 2630,2354 2535,2356"/>
        <Baseline points="2536,2359 2552,3267"/>
        <TextEquiv>
          <Unicode>○今案見論語陽</Unicode>
        </TextEquiv>
      </TextLine>
```

Annotations have been made on the [Calfa Vision platform](https://vision.calfa.fr), a free web-based annotation tool for documents and images designed for Oriental scripts.

## Some results

TBD

## Further readings

TBD

## Acknowledgments
