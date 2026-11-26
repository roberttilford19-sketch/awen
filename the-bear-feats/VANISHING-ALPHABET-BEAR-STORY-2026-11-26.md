# The Vanishing Alphabet — A Bear Story

DRAFT — NOT PUBLISHED

*The frame: this story is told in eight paragraphs, and the alphabet dies as it goes. The first paragraph uses all twenty-six letters. Then one letter dies at each step, in the order Z, Q, J, X, V, K, W, and is never used again — so the language tightens, paragraph by paragraph, all the way down.*

The bear began in the far west, carved from black jet by Zuni hands: a quick, quiet guardian no bigger than a thumb, with a red coral heartline running from his mouth along his flank to an arrowhead, and one turquoise eye. Packed in a box of soft cloth, he crossed plains and rivers on a long ride, exactly the sort of small, brave companion a man might keep — and he came at last to Hays, Kansas, and to Robert.

In the old teaching of the six directions, the bear stands at the west, guardian and master of that quarter, and his gifts are strength and healing. Robert learned this and liked the bear the more for it. A guardian you can hold in one hand, he thought, is a fine sort of guardian for a small apartment and a long life.

He rode in Robert's pocket most days, warm from the hand that held him, and in the evenings he sat on top of the refrigerator, a small blessing over the food of the house. Robert rubbed him in his palm when he prayed, the way a man turns a smooth stone, and the bear took the shine of it.

The bear is black stone, seven centimeters from nose to tail, light as a secret in the palm. The red line runs true along his side and ends in the arrowhead, and his one blue-green eye has seen the inside of a pocket, the top of a refrigerator, and the lamplight of a Kansas evening.

In time Robert moved him off the refrigerator and set him beside his books, out of the sun, in a place of honor among the stories. The bear did not mind. A guardian is patient, and stone is the most patient thing of all; he kept his post by the books the way he had kept it over the food.

Some mornings Robert lifts him and holds him to the light, and the red line along his side burns like a coal. The bear says nothing. He has said nothing in all his years, and still Robert hears him: be strong, be calm, bear up, and heal.

He rests now beside the stories Robert has made, in Hays, on a plain shelf in a small room. The sun does not find him there. He is safe from heat and harm, and his red heartline holds its fire in the shade, patient as stone, faithful as a dog that cannot stray.

One day, if the road is good, Robert means to carry him south to the land he came from, and set him in an artisan's hands, and say: see the little seam at the tip, mend it if you can. Until that day the bear abides in Hays, a small guardian at rest, his heartline red as a coal in the lamplight, his silence a blessing on the house.

---

## Desk record

Verification method: a Python script read the saved file, isolated the eight story paragraphs (the title, label, frame line, and this record are exempt), computed the set of letters a–z used in each paragraph (case-insensitive), and checked paragraph 1 for all 26 letters and each later paragraph against the cumulative death list (Z, then Z Q, then Z Q J, then Z Q J X, then Z Q J X V, then Z Q J X V K, then Z Q J X V K W). Results, run against the saved file on 2026-11-26:

- Paragraph 1: PASS — 26 of 26 letters used; none missing.
- Paragraph 2: PASS — no Z; 23 letters used.
- Paragraph 3: PASS — no Z, no Q; 22 letters used.
- Paragraph 4: PASS — no Z, no Q, no J; 22 letters used.
- Paragraph 5: PASS — no Z, no Q, no J, no X; 22 letters used.
- Paragraph 6: PASS — no Z, no Q, no J, no X, no V; 20 letters used.
- Paragraph 7: PASS — no Z, no Q, no J, no X, no V, no K; 20 letters used.
- Paragraph 8: PASS — no Z, no Q, no J, no X, no V, no K, no W; 19 letters used.

One repair was made during verification: paragraph 8 first carried the word "arrowhead," whose W broke the final ban; it now reads "the little seam at the tip," and the full check was re-run — all eight paragraphs PASS.
