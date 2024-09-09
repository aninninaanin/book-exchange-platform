{\rtf1\ansi\ansicpg1252\cocoartf2639
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 document.addEventListener('DOMContentLoaded', () => \{\
    const postBookForm = document.getElementById('post-book-form');\
    const searchButton = document.getElementById('search-button');\
    const searchQuery = document.getElementById('search-query');\
    const bookList = document.getElementById('book-list');\
    const myBooksList = document.getElementById('my-books-list');\
\
    let books = [];\
\
    // Handle book posting\
    postBookForm.addEventListener('submit', (e) => \{\
        e.preventDefault();\
\
        const title = document.getElementById('book-title').value;\
        const author = document.getElementById('book-author').value;\
        const genre = document.getElementById('book-genre').value;\
        const description = document.getElementById('book-description').value;\
        const image = document.getElementById('book-image').files[0];\
\
        const book = \{\
            title,\
            author,\
            genre,\
            description,\
            image: image ? URL.createObjectURL(image) : null\
        \};\
\
        books.push(book);\
        displayMyBooks();\
        postBookForm.reset();\
    \});\
\
    // Handle book searching\
    searchButton.addEventListener('click', () => \{\
        const query = searchQuery.value.toLowerCase();\
        const filteredBooks = books.filter(book =>\
            book.title.toLowerCase().includes(query) ||\
            book.author.toLowerCase().includes(query)\
        );\
\
        displayBooks(filteredBooks);\
    \});\
\
    function displayBooks(books) \{\
        bookList.innerHTML = books.map(book => `\
            <li>\
                <h3>$\{book.title\}</h3>\
                <p><strong>Author:</strong> $\{book.author\}</p>\
                <p><strong>Genre:</strong> $\{book.genre\}</p>\
                <p>$\{book.description\}</p>\
                $\{book.image ? `<img src="$\{book.image\}" alt="$\{book.title\}" style="max-width: 100px;"/>` : ''\}\
            </li>\
        `).join('');\
    \}\
\
    function displayMyBooks() \{\
        myBooksList.innerHTML = books.map(book => `\
            <li>\
                <h3>$\{book.title\}</h3>\
                <p><strong>Author:</strong> $\{book.author\}</p>\
                <p><strong>Genre:</strong> $\{book.genre\}</p>\
                <p>$\{book.description\}</p>\
                $\{book.image ? `<img src="$\{book.image\}" alt="$\{book.title\}" style="max-width: 100px;"/>` : ''\}\
            </li>\
        `).join('');\
    \}\
\});\
}