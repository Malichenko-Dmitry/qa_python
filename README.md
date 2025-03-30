# qa_python
test_add_new_book_add_two_books: Пример теста

test_add_new_book: Проверяет добавление новой книги.

test_add_new_book_duplicate: Проверяет, что дубликаты не добавляются.

test_add_new_book_too_long_name: Проверяет, что книга с названием более 40 символов не добавляется.

test_set_book_genre: Проверяет установку жанра для существующей книги.

test_set_book_genre_nonexistent_book: Проверяет, что нельзя установить жанр для несуществующей книги.

test_get_books_with_specific_genre: Проверяет получение книг по определенному жанру.

test_get_books_for_children: Проверяет, что книги с возрастным рейтингом не попадают в список для детей.

test_add_book_in_favorites: Проверяет добавление книги в избранное.

test_add_book_in_favorites_nonexistent_book: Проверяет, что нельзя добавить несуществующую книгу в избранное.

test_delete_book_from_favorites: Проверяет удаление книги из избранного.

test_get_list_of_favorites_books_empty: Проверяет, что список избранных книг пуст, если ничего не добавлено.

test_add_multiple_books_with_genres: Параметризованный тест для добавления нескольких книг с жанрами.
