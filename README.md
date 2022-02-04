# Sanskrit-English-Translation
Flow Diagram of Project

A. Dataset
The first dataset is scraped from http://www.sanskritbible.in/.
It includes a complete verse-by-verse translation of the
Christian Bible into Sanskrit. As JSON objects, we may query
the text pairs (Sanskrit Verse, English Verse). We converted
the different languages and verses into their own CSV files
after we received this query, so we could compare both
languages side by side .Also
https://www.holy-bhagavad-gita.org and ,
https://www.valmiki.iitk.ac.in have Sanskrit to English
translations that were scrapped and collected in a database.

Models implemented:
1. LSTM
2. GRU

Results:
Here are some outputs of GRU model:
Sanskrit sentence:
तदानीं यषूफ् उत्थाय रजन्यां शि शंुतन्मातरञ्च गहृीत्वा मि सर्देशं
प्रति प्रतस्थे,
Translated English Sentence:
Then Jesus answered had spoken to him, and said, I am to the
and the and the <EOS>
Some outputs of LSTM model:
Sanskrit sentence:
यीशस्ुतत् श्रत्ुवा तान् प्रत्यवदत,् नि रामयलोकानां चि कि त्सकेन
प्रयोजनंनास्ति , कि न्तुसामयलोकानांप्रयोजनमास्त।े
Translated English Sentence:
But when they heard that Jesus heard that they had not heard
that the the to the the the to the the <EOS>
