# gcis-site
Global Chromatic Identity State
GCIS — Global Chromatic Identity State
Format Specification License

Copyright © 2026 Benjamin Ryan
Keys, Codes & Modes™
Santa Barbara, California, USA
ben@keyscodesandmodes.com
https://gcis.keyscodesandmodes.com

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

CREATIVE COMMONS ATTRIBUTION 4.0 INTERNATIONAL (CC BY 4.0)

This specification — including the GCIS file format definition, field
schema, validation rules, vocabulary, and all associated documentation
and example files — is licensed under the Creative Commons Attribution
4.0 International License.

Full license text: https://creativecommons.org/licenses/by/4.0/legalcode

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

YOU ARE FREE TO:

  ✓  Implement — Build applications, plugins, tools, and services
                 that read, write, or validate .gcis files.

  ✓  Share      — Copy and redistribute this specification in any
                 medium or format.

  ✓  Adapt      — Build upon the specification, extend it, and
                 create derivative formats.

  ✓  Commercially use — Implement GCIS in commercial products
                        without royalty or restriction.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

UNDER THE FOLLOWING TERMS:

  ATTRIBUTION (Required)

  Any implementation, product, publication, or derivative work that
  uses, references, or builds upon the GCIS standard must include ALL
  of the following:

    1. The name of the originator:
       "Benjamin Ryan"

    2. The originating project:
       "Keys, Codes & Modes™"

    3. The specification URL:
       "https://gcis.keyscodesandmodes.com"

    4. The format version used:
       "GCIS v1.0" (or the version implemented)

  Suggested attribution for documentation, apps, and publications:

    "GCIS (Global Chromatic Identity State) format by Benjamin Ryan /
     Keys, Codes & Modes™ — https://gcis.keyscodesandmodes.com"

  Suggested attribution for UI and about screens:

    "Harmonic state: GCIS v1.0 — keyscodesandmodes.com"

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

TRADEMARK NOTICE

The following are trademarks of Benjamin Ryan and are NOT licensed
under CC BY 4.0. They may not be used in any product, service, or
publication without explicit written permission from Benjamin Ryan:

  • Keys, Codes & Modes™
  • 12-Color Chromatic Spectrum™
  • KCM Console™
  • FreeStyle® (registered trademark, 4 US Patents)

The GCIS format name and the .gcis file extension are descriptive
identifiers for the standard. You may use the terms "GCIS",
"Global Chromatic Identity State", and the .gcis extension freely
in implementations and documentation, provided attribution is given
as described above.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PATENT NOTICE

The FreeStyle® Musical Device (US Patents: 4 issued) is a separate
proprietary invention of Benjamin Ryan and is NOT part of the GCIS
open specification. The GCIS format does not implement or require
any patented invention.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

NO ADDITIONAL RESTRICTIONS

You may not apply legal terms or technological measures that legally
restrict others from doing anything this license permits.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

DISCLAIMER

THIS SPECIFICATION IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND.
BENJAMIN RYAN AND KEYS, CODES & MODES™ MAKE NO WARRANTIES, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, OR NON-INFRINGEMENT.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

CONTACT

For licensing questions, commercial partnerships, or to register
your application as a GCIS implementor:

  Benjamin Ryan
  Keys, Codes & Modes™
  1187 Coast Village Rd. #110
  Santa Barbara, CA 93108
  ben@keyscodesandmodes.com
  https://keyscodesandmodes.com

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

GCIS Version History

  v1.0  2026-04-25  Initial release
                    Fields: gcis, created, title, author, app,
                    state (root, mode, scale, activeNotes), history
                    Reference implementation: KCM Console v0.8.0

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
