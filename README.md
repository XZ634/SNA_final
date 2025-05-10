# Ideological Dynamics and Social Ties: A Social Network Analysis of Republican-Era Chinese Writers (1910–1949)

## 📂 Introduction

Following the fall of the Qing dynasty and the rise of the Republic of China, Chinese writers became active participants in cultural and political reform movements. Through literary societies, publications, and personal connections, these writers not only reshaped Chinese literature but also became deeply involved in ideological debates, particularly the growing influence of leftist thought.

This project investigates the social networks among Republican-era Chinese writers (1910–1949) to understand how these networks were structured and how they may have influenced the spread of leftist ideology. Specifically, the study explores whether ideological alignment shaped social connections, whether occupying central network positions translated into political power, and whether social ties influenced writers' political risks, such as persecution in the Mao era.

Using newspaper co-occurrence data and applying social network analysis methods, this research seeks to offer new insights into the intersection of literary, ideological, and political dynamics in modern Chinese history.

## 📥 Data

-   **Network Data**: `data/overall_data.xlsx`, `data/1910-1919_data.xlsx`, `data/1920-1929_data.xlsx`, `data/1930-1939_data.xlsx`, `data/1940-1949_data.xlsx`\
    -   Co-occurrence networks based on Republican-era newspaper coverage (1910–1949), across four historical periods.
    -   Media exposure measured by the number of newspaper pages mentioning each writer.
-   **Node Attributes**: `data/left_wing.xlsx`, `data/constants.xlsx`
    -   Leftist ideological coding (0–3) based on historical biographical data.
    -   Biographical attributes including gender, age, hometown, education background (Japan/West), and literary society membership.

## 🔧 Key Findings

1.  **Network Structure**
    -   The writer network shows significant triadic closure, indicating small, cohesive social circles.
    -   Media exposure strongly increases a writer's likelihood of forming social ties.
    -   Writers of similar age or from the same hometown are more likely to connect.
2.  **Role of Education**
    -   Japanese-educated writers are more active in forming connections, but less likely to connect with each other.
    -   Western education is negatively associated with adopting leftist positions, though the effect is not statistically robust.
3.  **Ideological Dynamics**
    -   Leftist writers are more likely to connect with each other (homophily), but no evidence suggests that leftist ideology spreads through the network.
4.  **Literary Societies**
    -   Members of older societies like the Creation Society are less connected, while members of the Left-Wing Writers’ League show strong internal cohesion.
5.  **Post-Civil War Outcomes**
    -   Non-leftist writers tended to leave for Taiwan, while those who stayed included both leftist and non-leftist figures.
    -   Leftist loyalty and early revolutionary credentials (e.g., early CCP membership) appear to protect writers from political persecution more effectively than network position alone.

## 📂 Contributions

-   Introduces newspaper co-occurrence data to study Chinese literary history.
-   Offers new insights into how social structures and ideology interacted in shaping literary and political communities.
-   Proposes a network-based perspective on understanding the Chinese Communist Party’s rise and the dynamics of political persecution in Mao-era China.

## 📥 Limitations

-   Small sample of 28 writers limits generalizability.
-   Ideological coding based on subjective interpretation of biographies.
-   Network based on co-occurrence lacks validation through alternative sources like biographies or correspondence.
-   Some counterintuitive findings (e.g., Japanese-educated writers' disconnection) remain unexplained.
-   No evidence found for ideology diffusion via social ties, possibly due to data limitations.

## 🔧 Future Directions

-   Expand to include more writers and socio-economic attributes.
-   Validate networks with richer historical data.
-   Apply text-as-data methods to objectively measure ideological positions.
-   Explore alternative network definitions to better capture influence and diffusion mechanisms.
