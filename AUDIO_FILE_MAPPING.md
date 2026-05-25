# Audio File Mapping

This document maps shortened file names to their original long filenames in the repository.

## File Mapping

| Short Name | Original Filename |
|---|---|
| `05_Advancement.mp3` | `Culture Lab from Western States Center - Smoke & Mirrors - 05 Advancement featuring evan milligan, James Gardin and Juicyy Da Master.mp3` |
| `07_Innerstates.mp3` | `Culture Lab from Western States Center - Smoke & Mirrors - 07 Innerstates featuring Dope Doodie and evan milligan.mp3` |
| `10_Field.mp3` | `Culture Lab from Western States Center - Smoke & Mirrors - 10 Shake the Field featuring Juiccy Da Master and Felt Five with Brezzy Monroe, evan milligan and Zoey Jackson.mp3` |
| `07_Dogon.mp3` | `Shake the Field and Felt Five - Caregiver Road Trip- Remix Edition - 07 Beyond- The Dogon Have Landed Near Guntersville.mp3` |
| `15_Narissa.mp3` | `Shake the Field and Felt Five - Caregiver Road Trip- Remix Edition - 15 Narissa's Home (Album Remix).mp3` |

## Usage

When coding, reference the short names (e.g., `05_Advancement.mp3`) in your HTML/JavaScript, but link to the full paths of the original files in your repository.

Example:
```html
<audio controls>
  <source src="Culture%20Lab%20from%20Western%20States%20Center%20-%20Smoke%20%26%20Mirrors%20-%2005%20Advancement%20featuring%20evan%20milligan%2C%20James%20Gardin%20and%20Juicyy%20Da%20Master.mp3" type="audio/mpeg">
</audio>
```

You can reference this mapping document to use the short names as identifiers in your code.
