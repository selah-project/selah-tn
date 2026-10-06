# DINTLHA — Phetolelo ya Setswana ya Selah

Faele e e tshwara **ditemana tse seatla sa motho kgotsa tshwetso e di amileng** — gore
mmadi yo o tlhatlhobang temana nngwe le nngwe a kgone go bona gore e dirilwe ke motshine,
ka seatla, kgotsa ka fa tlase ga tshwetso, le gore ka ntlha yang. E tshwara gape ditshwetso
ka ga mafoko mangwe, ditemana tse di thata, le dipotso tse di sa ntseng di bulegile mme di
emetse tsebe ya Setswana.

Tsenyo nngwe le nngwe e naya temana · se se dirilweng · lebaka · letlha. Sehebera se mo
tsenyong nngwe le nngwe. **Ditsenyo di kwadilwe ka Seesemane** fa di umaka sebopego sa
mafoko a Sehebera — Seesemane ke puo ya tiro e e kopanyang diphetolelo tsotlhe tsa Selah.
Ditsenyo di a baakanngwa, ga di phimolwe ka sephiri — hisitori ya polokelo ke karolo ya
bosupi.

Bala `PROVENANCE.md` go itse gore mokwalo o dirilwe jang, le `CONTRIBUTING.md` pele o
baakanya sepe.

---

## §1 · Verses written by hand

None. Every verse in this repository was produced by the machine under the written rules
(`tn.md`). Where a verse was faulty it was **rendered again**, not patched by hand — with
one mechanical exception, recorded in §5.

## §2 · Words fixed in the rules while the work ran

Each of these was added to the rules (`tn.md`) during the rendering, on 2026-10-03, after
the fault was seen in verses already written. Verses written before a fix were rendered
again at the end (§5).

- **Botswana spelling, not South African** · the first verses wrote *setšhaba* /
  *ditšhaba*, the South African spelling. The rules had chosen Botswana `tsh`:
  **setshaba** · **ditshaba** · **setshabeng**. Fixed by name.
- **Northern Sotho words, not Setswana** · *mošomi* · *mošomo* · *letšatši* · *mašemo* ·
  *bolwetši* · *lentšu* appeared. Setswana has its own: **modiri** · **tiro** ·
  **letsatsi** · **masimo** · **bolwetse** · **lefoko**. The list alone did not hold, so the
  words were then fixed **by Hebrew**, in the core-word table: `יצא` (hiphil) → **ntsha** ·
  **ntshiwa**, not *ntšha* / *ntšhwa*; `גוים` → **ditshaba**; `עבד` · `עבודה` → **modiri** ·
  **tiro**; `קול` · `דבר` → **lentswe** · **lefoko**; `שאל` → **potso** · **go botsa**;
  `חדר` → **phaposi**; `משל` (to rule) → **go busa**. The table held better than the list;
  it did not hold completely (§3).
- **No article, no English in brackets** · Setswana has no article. Some verses carried
  `⟨the⟩` or `⟨ה⟩` in the brackets — English copied from the examples in the instructions.
  Ruled: the Hebrew article `ה-` is not written; a bracket holds `⟨את⟩` or a word
  **Setswana** needs (*⟨ke⟩* · *⟨o⟩* · *⟨mo⟩*), nothing else.

## §3 · Known faults — open

These verses are to be rendered again. They stand here so nobody reads them as settled.
The repository is being re-checked as this is written; this list is not a final count.

### The verse that does not read

- **Daniel 1:6** · the flow repeats *ba Yahunta* and says the boys were *speaking
  Setswana*; the names `דניאל חנניה מישאל ועזריה` are in the word rows but missing from
  the flow. The flow must be rendered again from the rows.
- **Numbers 24:3** · `וישא משלו ויאמר` — *he took up his oracle and said* — reads *a
  tlhatloga ⟨molao⟩ wa kgakololo ya gagwe*. A bracketed word the Hebrew did not write, and
  the sense lost.

### Northern Sotho and Sesotho

- **`š` spellings** · after two rounds of rendering again, a remainder of verses still
  carries `š`, which the rules forbid. Two different things are mixed in it:
  - **Northern Sotho words** — Gen 30:4 *mošomi* for `שפחה` (the handmaid). A fault.
  - **The word *new*** (`חדש`) — Exod 1:8 *kgosi e ntšhwa*, Ps 149:1 *pina e ntšha*,
    Ezek 11:19 *ruakh e ntšha*, Isa 43:19 *se seša*, Ps 104:30 *ntšhafatsa*. Setswana
    writing may itself spell *new* with `š`. If so, **the rule is wrong here, not the
    verses** — and that would explain why fixing it by name never held. Open, for a native
    ear, before anything is rendered again on this account.
  - Also listed: Gen 30:37, Lev 13:17, Prov 3:10.
- **Job 29:15** · `עינים` → *mahlo* — the Sesotho form; Setswana is **matlho**. In the same
  verse `פסח` (*lame*) → *leswe*, which is *dirt*.

### Hidden foreign letters

- **1 Chr 1:32** · *Shuakhе* — the last letter is Cyrillic `е` (U+0435), not Latin `e`.
  Invisible to the eye.

### Wrong words

- **Gen 1:2** · `על־פני` twice → *mo seatleng sa*, *in the hand of*. `פני` is **face**:
  *mo godimo ga sefatlhego sa*. Elsewhere `פני` mostly comes out as the preposition
  *pele ga* (*before*), which is lawful.
- **Exod 32:8** · `עגל` → *podi*, a **goat**. The Hebrew is a **calf** (*namane*). The
  word `עגל` has come out several ways across the corpus — *namane*, *kgwanyana*,
  *nonwane*, *podi* — and wants one Setswana word from a native ear.
- **Lev 13:17** · the flow adds *moporofeti-a-kgosi wa tumo* before `הכהן` (the priest),
  which the rows render *moruti* alone; and `וטהר` (*pronounce clean*) comes out
  *itshepisa*, *make holy*. Clean and holy are two different Hebrew words.

### Rows that do not match the Hebrew

- At the end of the work, a set of verses was found where the word rows did not match the
  Hebrew tokens one for one, or where the `⟨את⟩` in the flow did not match the rows. They
  are listed, verse by verse, and are being rendered again. If a verse's flow and rows
  disagree, the rows are the record.

## §4 · Lawful words — do not correct

- **`modimo` / `medimo`** in lower case · lawful for the gods of the nations and for idols.
  Only `Modimo` standing where `יהוה` or `אלהים` stands is the fault.
- **`ngaka`** · rejected for `נביא` (prophet). But lawful where the Hebrew means a healer
  — Jer 8:22 `רפא`, *A ga go na ngaka koo?* — and found in Gen 44:15 (`נחש`, Joseph's
  divining) and Isa 29:4 (*ngaka ya
  bapontsho*, `אוב`, the medium). Read each before calling it a fault.
- **`Morena wa me`** · Gen 44:19, Judah to Joseph: `אדני` said to a man. Lawful.
- **`go bua Yahwe`** · `נאם יהוה`, always (Jer 23:24, twice in the verse). Before a man's
  name, `נאם בלעם` is **lefoko la Bileame** (Num 24:3).
- **`Ehyeh`** · Exod 3:14, `אהיה אשר אהיה`, left in the Hebrew.
- **Prov 25:2** · `כבד` → **kgalalelo** twice, `דבר` → **lefoko** twice — the mirror of the
  verse stands in Setswana.

## §5 · The end of the work

The rendering ended on 2026-10-03, about 23:28. At once every verse the end-of-work check
had flagged — the Name in the wrong seat, English, English in brackets, Hebrew left in
the flow, Northern Sotho and Sesotho spellings, hollow files — was removed and rendered
again, in two rounds, finishing at 23:53.

Where a verse rendered again lost an `⟨את⟩` that the earlier version had matched to its
rows, and the earlier version's only fault was an English `⟨the⟩` or `⟨ה⟩`, the earlier
version was **restored with that bracket removed** — a mechanical change, checked against
the rows. Every other verse rendered again was kept as rendered.

Where a Hebrew surface word in a row had been altered, it was restored from the Hebrew
text.

## §6 · Open questions — waiting for an ear

1. **`Elohim`** — or **`Elohime`**, with a final vowel as Setswana gives other names?
2. **`ruakh` · `Mashiakh` · `minkha`** — `kh` for `ח`, or `h`?
3. **`moporofeti`** for `נביא` — or *nabi*?
4. **Names** (*Abrahame* · *Yitshake* · *Dawide*) — the Hebrew sound against the familiar
   forms.
5. **`leje` or `lefika`** for `אבן`? **`lebati` or `kgoro`** for `דלת`?
6. **`sefatlhego` or `sefathego`** for `פנים` — both appear.
