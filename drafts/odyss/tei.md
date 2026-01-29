

### Unit Mapping
The TITUS 1 structural units are mapped onto TEI as follows:

| Source Unit | TEI Mapping | Notes |
|-------------|-------------|-------|
| Chapter | `div@chapter` | Automatically translated into named div |
| Verse | `l` |  |

### Structural overview
```text
text (@xml:lang=grc-Grek-x-homeric)
  body
    div (@data-level=1, @n, @type=chapter, @xml:id) (multiple)
      head (@xml:lang=grc-Grek) (multiple)
      l (@n, @xml:id) (multiple)
```

### Structure Example

```xml
<div xmlns="http://www.tei-c.org/ns/1.0" n="1" xml:id="chapter-1" type="chapter" data-level="1">
				<head xml:lang="grc-Grek">ΟΔΥΣΣΕΙΑΣ Α</head>
				<l n="1" xml:id="chapter-1-l-1">῎Ανδρά μοι ἔννεπε, Μοῦσα, πολύτροπον, ὃς μάλα πολλὰ</l>
				<l n="2" xml:id="chapter-1-l-2">πλάγχϑη, ἐπεὶ Τροίης ἱερὸν πτολίεϑρον ἔπερσε·</l>
				<l n="3" xml:id="chapter-1-l-3">πολλῶν δ' ἀνϑρώπων ἴδεν ἄστεα καὶ νόον ἔγνω,</l>
				<l n="4" xml:id="chapter-1-l-4">πολλὰ δ' ὅ γ' ἐν πόντῳ πάϑεν ἄλγεα ὃν κατὰ ϑυμόν,</l>
				<l n="5" xml:id="chapter-1-l-5">ἀρνύμενος ἥν τε ψυχὴν καὶ νόστον ἑταίρων.</l>
				<l n="6" xml:id="chapter-1-l-6">ἀλλ' οὐδ' ὧς ἑτάρους ἐρρύσατο ἱέμενός περ·</l>
				<l n="7" xml:id="chapter-1-l-7">αὐτῶν γὰρ σϕετέρῃσιν ἀτασϑαλίῃσιν ὄλοντο,</l>
				<l n="8" xml:id="chapter-1-l-8">νήπιοι, οἳ κατὰ βοῦς ῾Υπερίονος ᾽Ηελίοιο</l>
				<l n="9" xml:id="chapter-1-l-9">ἤσϑιον· αὐτὰρ ὁ τοῖσιν ἀϕείλετο νόστιμον ἦμαρ.</l>
				<l n="10" xml:id="chapter-1-l-10">τῶν ἁμόϑεν γε, ϑεά, ϑύγατερ Διός, εἰπὲ καὶ ἡμῖν.</l>
  ...
```
