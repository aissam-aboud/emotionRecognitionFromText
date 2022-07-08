# Emotion Classification in Short Messages

Multi-class sentiment analysis problem to classify texts into five emotion categories : 𝐣𝐨𝐲, 𝐬𝐚𝐝𝐧𝐞𝐬𝐬, 𝐚𝐧𝐠𝐞𝐫, 𝐟𝐞𝐚𝐫, 𝐧𝐞𝐮𝐭𝐫𝐚𝐥. A great project to go through different text classification techniques. This includes 𝐝𝐚𝐭𝐚𝐬𝐞𝐭 𝐩𝐫𝐞𝐩𝐚𝐫𝐚𝐭𝐢𝐨𝐧 (𝐭𝐞𝐱𝐭 𝐓𝐨𝐤𝐞𝐧𝐢𝐳𝐚𝐭𝐢𝐨𝐧 by spliting the text into word tokens and 𝐫𝐞𝐦𝐨𝐯𝐢𝐧𝐠 𝐧𝐨𝐢𝐬𝐞 : html markups, urls, non-ascii symbols, trailing whitespace etc), 𝐏𝐚𝐝𝐝𝐢𝐧𝐠 and 𝐄𝐧𝐜𝐨𝐝𝐢𝐧𝐠), 𝐭𝐫𝐚𝐝𝐢𝐭𝐢𝐨𝐧𝐚𝐥 𝐦𝐚𝐜𝐡𝐢𝐧𝐞 𝐥𝐞𝐚𝐫𝐧𝐢𝐧𝐠 with scikit-learn (𝐑𝐚𝐧𝐝𝐨𝐦 𝐅𝐨𝐫𝐫𝐞𝐬𝐭, 𝐋𝐨𝐠𝐢𝐬𝐭𝐢𝐜 𝐑𝐞𝐠𝐫𝐞𝐬𝐬𝐢𝐨𝐧, 𝐋𝐢𝐧𝐞𝐚𝐫 𝐒𝐮𝐩𝐩𝐨𝐫𝐭 𝐕𝐞𝐜𝐭𝐨𝐫), 𝐧𝐞𝐮𝐫𝐚𝐥 𝐧𝐞𝐭𝐰𝐨𝐫𝐤𝐬 (tensorflow keras).

The dataset that we did used consists of two columns. The first columns containing short texts, mainly short messages and dialogs. The second columns have the emotion present in the text.

Also, in this project i had the chance to take a look at the word embedding technique (𝐎𝐧𝐞-𝐡𝐨𝐭 representation and the 𝐖𝐨𝐫𝐝2𝐯𝐞𝐜 modal) which is in general converting each word in our dataset to a vector of numbers so the machine can understand and get the similarity between words. The reason behind this is that we need to train our modal so it can predict the emotion exists in a sentence based on the context.
