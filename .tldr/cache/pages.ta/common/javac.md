# javac

> ஜாவா பயன்பாட்டு தொகுப்பாளர்.
> மேலும் விவரத்திற்கு: <https://docs.oracle.com/en/java/javase/17/docs/specs/man/javac.html>.

- ஒரு `.java` கோப்பை தொகுக்கவும்:

`javac {{கோப்பு.java}}`

- பல `.java` கோப்புகளை தொகுக்கவும்:

`javac {{கோப்பு1.java}} {{கோப்பு2.java}} {{கோப்பு3.java}}`

- தற்போதைய கோப்பகத்தில் அனைத்து `.java` கோப்புகளையும் தொகுக்கவும்:

`javac {{*.java}}`

- ஒரு `.java` கோப்பை தொகுத்து அதன் விளைவாக வரும் கிளாஸ் கோப்பை ஒரு குறிப்பிட்ட கோப்பகத்தில் வைக்கவும்:

`javac -d {{அடைவிற்குப்/பாதை}} {{கோப்பு.java}}`