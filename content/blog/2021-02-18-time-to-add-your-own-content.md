---
createdAt: 2021-02-18
title: Time to add your own content
description: Remove all of the .md-files in the /content folder and go at it!
---

<divider></divider>

<paragraph>
 <template #content>
 We believe that ever-evolving technology and great user experiences are the key to sustainable success in any industry. We employ some of the best experts in tech to build solutions that inherently encourage growth, speed and constant renewal. We are experts at what we are doing, but not at what we will be doing in a few years. To make sure this message will always ring true, we created an environment and working methodology in which continuous evolution is the key to success. Our solutions are build to inherently encourage growth, speed and constant renewal.
</template>

</paragraph>

<Intro>About the news detail is here
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</Intro>

## Sit liquentibus sinu verbis et spatiarer laedar

Lorem markdownum viros voce nostri tumulandus contegat tua **prior** umbra
**Pelopeia**. Fertur in nocet edidit Thyneius cornu; est aether senioribus illa
detinet moenia horrendus viri. Amo tophis Idaeis [blog](/blog)
venerat.

Sic **nostrae habet**: este, sua illic auctor causam. Pateres argentea, nati
ictus nondum, redeuntia vertitur ulterius quae temone potentia dominos obstitit
dat: voce quater attritas. Imagine quamquam quoque
[projects](/projects) et sonabat Cybeleius
albentes primaque sidera, omnia.

## Apud sunt

Addidit nunc: finita tua celatos vacuos Morpheus tigridis videre. Et an in ne
scelus pluviaque fluitque consurgere dixit inficit est fecere atque voce perque
fuit ulla Thestorides. Suas adveniens vituli hi quem quaecumque Argos, frustra
solacia: inpensior munere quae. Vivacisque **nos has** elusaque Aeaciden altum
oris ille convicia castique.

```js{1,4}[posts.vue]
formatDate(dateString) {
  const date = new Date(dateString)
  return date.toLocaleDateString(process.env.lang) || ''
},
async fetchPosts(
    postType = this.postType,
    amount = this.amount,
    sortBy = this.sortBy,
  ) {
  return this.$content(postType)
    .sortBy(sortBy.key, sortBy.direction)
    .limit(amount)
    .fetch()
    .catch((err) => {
      error({ statusCode: 404, message: amount > 1 ? 'Posts not found' : 'Post not found' })
    });
}
```

## Est nec scrobibus Antissa

Duroque _sunt aureus partem_ concava soleant et limite frugum Typhoea omnique:
que et et sono meum. Relinquit miscet est humum, quo taceam lacrimas gratissima
vetustas, Syrtis urguent valle referebam nostris iustis, fiet! Deos per totidem
agris! Unumque incursat, dedere Libycas sensit; hac horto Lucifero dissaepserat
aliud. Aeginam memorabile sororibus excepto.

> Nato stella sensit copia prensantem ille annis quoniam Messapiaque inquit male
> pater ex iuventae, casses? **Velle** esse, Apis purpureis illa adicit, sit
> totum tu, **mihi** ego multa et fieri. Acu Cipe ut relabens capillos per:
> scelus arae conplevit torquet. Inrita hortaturque tumultus superest tamen
> respiramina per diu arasque manus **prope Echionio** Troades, est. Tempus
> arbore in ita.

Ad celeri est et Tremorque reliquerat fruges inplicuit. Dictis libratum
[cuncta](http://quisquis.com/) intentare essent, terribilesque quam sorores arce
oscula inornatos quam sole erat in ignavus comis tibi. Latoius cernentem es hunc
ferunt Ionio nec saucia cupiunt erat. Et petiit gesserat iudicium libido
elususque fugere armiferos placet, illae.
