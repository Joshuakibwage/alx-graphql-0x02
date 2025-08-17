# Rick and Morty Episodes Explorer 🎬🛸

A modern React + Next.js application that queries the **Rick and Morty GraphQL API** to display episodes in a responsive grid. Built as part of the **ALX GraphQL learning series (alx-graphql-0x02)**.

---

## 🚀 Features
- 🔗 **GraphQL + Apollo Client** – Fetch paginated episode data from the Rick and Morty API.
- 🎨 **Modern UI with TailwindCSS** – Responsive grid layout, hover effects, and gradients.
- 📱 **Responsive Design** – Optimized for desktop, tablet, and mobile.
- ⏪⏩ **Pagination** – Easily browse through episodes with "Previous" and "Next" controls.
- ♻️ **Reusable Components** – Episode cards separated into their own component.

---

## 📂 Project Structure

alx-rick-and-morty-app
│── components/
│ └── common/
│ └── EpisodeCard.tsx # Reusable episode card component
│
│── interfaces/
│ └── index.ts # TypeScript interfaces & props definitions
│
│── pages/
│ └── index.tsx # Home page, GraphQL query, pagination
│
│── graphql/
│ └── queries.ts # GraphQL queries (GET_EPISODES)
│
│── public/ # Static assets (if any)
│
└── README.md


---

## 🛠️ Tech Stack
- [Next.js](https://nextjs.org/) – React framework
- [TypeScript](https://www.typescriptlang.org/) – Strong typing
- [Apollo Client](https://www.apollographql.com/docs/react/) – GraphQL queries
- [TailwindCSS](https://tailwindcss.com/) – Utility-first CSS framework
- [Rick and Morty API](https://rickandmortyapi.com/graphql) – GraphQL endpoint

---

## ⚡ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Joshuakibwage/alx-graphql-0x02.git
cd alx-graphql-0x02/alx-rick-and-morty-app

2. Install dependencies

npm install

3. Run the development server

npm run dev

4. Open in browser

Visit 👉 http://localhost:3000
📖 Code Overview

    EpisodeCard.tsx

        Displays episode info (name, code, air date).

        Includes hover animation and badge for episode code.

    index.tsx

        Fetches episodes via useQuery(GET_EPISODES).

        Implements pagination (setPage with refetch).

        Maps API results into EpisodeCard.

🎨 Preview

Here’s what the app looks like:

🟦 Rick and Morty Episodes
| Episode Name        | Episode Code | Air Date    |
|---------------------|--------------|-------------|
| Pilot               | S01E01       | Dec 2, 2013 |
| Lawnmower Dog       | S01E02       | Dec 9, 2013 |
| ...                 | ...          | ...         |

📌 To Do / Possible Improvements

    🔍 Add search/filter by episode name.

    🌍 Add character previews per episode.

    📱 Improve mobile pagination UI.

    💾 Cache GraphQL queries for faster navigation.

👨‍💻 Author

Built with 💙 during the ALX GraphQL learning project.
Connect with me on LinkedIn: 🌍https://www.linkedin.com/in/joshua-kibwage-b19556321/
