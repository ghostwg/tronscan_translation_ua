
export const messages = {
/*
##################################################################################
#                                                                                #
#  $$$$$$$$\                                                                     #
#  \__$$  __|                                                                    #
#     $$ | $$$$$$\   $$$$$$\  $$$$$$$\   $$$$$$$\  $$$$$$$\$$$$$$\  $$$$$$$\     #
#     $$ |$$  __$$\ $$  __$$\ $$  __$$\ $$  _____|$$  _____\____$$\ $$  __$$\    #
#     $$ |$$ |  \__|$$ /  $$ |$$ |  $$ |\$$$$$$\  $$ /     $$$$$$$ |$$ |  $$ |   #
#     $$ |$$ |      $$ |  $$ |$$ |  $$ | \____$$\ $$ |    $$  __$$ |$$ |  $$ |   #
#     $$ |$$ |      \$$$$$$  |$$ |  $$ |$$$$$$$  |\$$$$$$$\$$$$$$$ |$$ |  $$ |   #
#     \__|\__|       \______/ \__|  \__|\_______/  \_______\_______|\__|  \__    #
#                                                                                #
##################################################################################
#                                                                                #
#         Template for translating the tronscan.org website                      #
#         Version: 1.3-12062018                                                  #
#         Update Date: 15.06.2018                                                #
#         Language: Ukrainian                                                    #
#         Status: Approved Version                                               #
#         Number of checks: 2                                                    #
#         Participants: Rovak,PMD3VSolution,DrKaradenizli                        #
#                                                                                #
##################################################################################
#                                                                                #
# description and structure of the template                                      #
#                                                                                #
# "<name of the variable>": "<corresponding translation>"                        #
#                                                                                #
# Note: please concentrate only on the value <corresponding translation>         #
#                                                                                #
##################################################################################
#                                                                                #
# global section                                                                 #
#                                                                                #
##################################################################################
*/
  // button description - OK (confirm)
  "ok": "OK",
  // title - Tron protocol
  "app_title": "Tron Protocol",
  // description of an input field  (enter the password)
  "password": "Пароль",
  // description of a display field - price
  "money_price": "ціна",
  // description of a display field - price
  "price": "ціна",
  // blockchain -> blocks - plural
  "blocks": "блоки",
  // blockchain -> block - singular
  "block": "блок",
  // description of a display field - name
  "name": "ім'я",
  // website
  "website": "вебсайт",
  // Tron TRX address eg. TScGuWDzgLD2...opywfkDMCh77
  "address": "адреса",
  // button description - sign out (account)
  "sign_out": "вихід",
  // button description - sign in (account)
  "sign_in": "вхід",
  // button description - Register / Log-in (account)
  "register_login": "Реєстрація / Вхід",
  // button description - Register (account)
  "register": "реєстрація",
  // button description - Login (account)
  "login": "вхід",
  // row description - height/size of a block
  "height": "висота",
  // row description - age of the block
  "age": "вік",
  // row description - size of the block (bytes)
  "bytes": "байтів",
  // row description - eg. produced by XXX
  "produced by": "вироблено",
  // row description - which contract is assigned
  "contract": "Контакти",
  // text module (send XXX from ...to)
  "from": "від",
  // text module (send XXX from ...to)
  "to": "до",
  // userfield description
  "value": "значення",
  // statistic informations (total number of accounts)
  "total_accounts": "Всього Облікових записів",
  // button description - submit (confirm)
  "submit": "підтвердити",
  // button description - send trx
  "send": "відправити",
  // button description - receive trx
  "receive": "отримати",
  // button description - supply
  "supply": "запас",
  // button description - to view more informations
  "view": "перегляд",
  // button description - to view all informations
  "view_all": "Подивитись все",
  // button description - to create an account or token
  "create": "Створити",
  // information field - country
  "country": "Регіон",
  // field description - eg. amout: 20 trx
  "amount": "кількість",
  // button description (to show the own votes)
  "my_vote": "мої голоси",
  // button description (to submit the vote)
  "submit_votes": "проголосувати",
  // subtitle - statistic information - accounts(plural)
  "accounts": "облікові записи",
  // description - created
  "created": "створений",
  // description field - name of the exchange
  "exchange": "біржа",
  // button description - next (go to the next step)
  "next": "наступний",
  // infomessage - button action message -> Copied to clipboard
  "copied_to_clipboard": "Скопійовано в буфер обміну",
  // button description - Cancel
  "cancel": "Відмінити",
  // button description - Reset
  "reset": "Скинути",
  // error message title - Error
  "error": "Помилка",
  // statusmessage - Title
  "unlock_keyFile": "Відкрити KeyFile",
  // errormessage - no password entered
  "enter_password_message": "Вам потрібно ввести пароль!",
  // errormessage - wrong password
  "password_incorrect":"Невірний пароль",
  // button description - Try again
  "try_again": "Спробуйте ще",

/*
##################################################################################
#                                                                                #
# navigation section                                                             #
#                                                                                #
##################################################################################
*/
  // navigation bar -> topic - Blockchain
  "blockchain": "Блокчейн",
  // navigation bar -> topic - Wallet
  "wallet": "Гаманець",
  // navigation bar -> topic - Home (main page)
  "home": "Головна",
  // navigation bar -> topic - Transfers
  "transfers": "передачі",
  // navigation bar -> topic - Live (view live information, current transfers)
  "live": "Наразі",
  // navigation bar -> topic - Statistics (statistic informations)
  "statistics": "Статистика",
  // navigation bar -> topic - "Markets" (trx exchanges and current prices)
  "markets": "Ринки",
  // navigation bar -> topic - Tools
  "tools": "Інструменти",
  // navigation bar -> topic - Transaction Viewer (tool to get transaction informations)
  "transaction_viewer": "Переглядач транзакцій",
  // navigation bar -> topic - Node Tester (tool to test the tron node connectivity)
  "node_tester": "Тест вузлу",
  // navigation bar -> topic - System (blockchain informationen)
  "system": "Система",
  // navigation bar -> topic News (to get current informations about tron and tronscan)
  "news": "Новини",
  // navigation bar -> topic - Help (report a bug and view the documentation)
  "help": "Допомога",
  // navigation bar -> topic - Nodes (infomations about the active tron nodes)
  "nodes": "Вузли",
  // navigation bar -> topic - Votes (area to vote a SR)
  "votes": "Голоси",
  // navigation bar -> topic - Account (personal account area)
  "account": "Обліковий запис",
  // navigation bar -> tokens
  "tokens": "Токени",
  // navigation bar -> topic - Token->Overview (get an overview of the tokens)
  "overview": "Огляд",
  // navigation bar -> topic - Participate (buy a token)
  "participate": "брати участь",

/*
##################################################################################
#                                                                                #
# home dashboard                                                                 #
#                                                                                #
##################################################################################
*/
  // title of the main page
  "tron_main_message": "Децентралізація в Інтернеті",
  // subtitle - realtime information - how many transactions last hour
  "transactions_last_hour": "Транзакцій за останню годину",
  // subtitle - realtime information - current block height
  "block_height": "Висота блоку",
  // subtitle - realtime information - how many online nodes
  "online_nodes": "Вузлів онлайн",
  // subtitle - realtime information - current price per 1000 trx
  "pice_per_1000trx": "Ціна (за 1000TRX)",
  // hyperlink description - to vote for the super representatives
  "vote_for_super_representatives": "Голосування за Супер-представників",
  // hyperlink description - to view the super representatives
  "view_super_representatives": "Огляд Супер-представників",
  // hyperlink description - to create a new wallet
  "create_new_wallet": "Створити новий Гаманець",
  // hyperlink description - to view the tokens
  "view_tokens": "Перегляд Токенів",

/*
##################################################################################
#                                                                                #
# tableinformations and statistics                                               #
#                                                                                #
##################################################################################
*/
  // button description -> table navigation -> first page
  "first_page": "перша сторінка",
  // button description -> table navigation -> previous page
  "previous_page": "попередня сторінка",
  // button description -> table navigation -> next page
  "next_page": "наступна сторінка",
  // button description -> table navigation -> last page
  "last_page": "остання сторінка",
  // table description -> Page 2 of 3
  "page": "сторінка",
  // table description -> Page 2 of 3
  "of": "з",
  // information field - statistics - in which country are the most nodes e.g. USA ... Most Nodes
  "most_nodes": "Більшість Вузлів",
  // status message - loading informations - loading Node informations
  "loading_nodes": "завантаження Вузлів",
  // table information - row title (hostname->Node)
  "Hostname": "Ім'я хосту",
  // table information - row title (last update from tron node)
  "Last Update": "Останне оновлення",
  // status message - waiting for syncing the first node
  "first_node_sync_message": "Очікування першої синхронізації вузла, будь ласка спробуйте ще за кілька хвилин.",
  // table information - row title - statistics -  last created block (blockchain)
  "last_block": "останній блок",
  // table information - row title - statistics - Blocks Produced (blockchain)
  "blocks_produced": "Блоків Вироблено",
   // table information - row title - statistics - Blocks Missed (blockchain)
  "blocks_missed": "Блоків пропущено",
  // table information - row title - statistics - productivity
  "productivity": "продуктивність",
  // table information - row title - statistics - rewards
  "rewards": "винагорода",

/*
##################################################################################
#                                                                                #
# blockchain - statistics                                                        #
#                                                                                #
##################################################################################
*/
  // subtitle - statistic information eg. diagram -> top 25 addresses
  "addresses": "адреси",
  // subtitle - statistic information eg. diagram -> TRX transferred in the past hour
  "trx_transferred_past_hour": "Кількість TRX переданих за останню годину",
  // subtitle - statistic information eg. diagram -> Transactions in the past hour
  "transactions_past_hour": "Транзакції за останню годину",
  // subtitle - statistic information eg. diagram -> Average Block Size
  "average_blocksize": "Середній розмір блоку",
  // table header
  "rich_list": "Список Багатіїв",

/*
##################################################################################
#                                                                                #
# account section                                                                #
#                                                                                #
##################################################################################
*/
  // title/headline of the form
  "set_name": "Встановити Ім'я",
  // statusmessage
  "unique_account_message": "Ви можете вказати ім'я свого облікового запису лише один раз!",
  // button description
  "change_name": "Змінити ім'я",
  // placeholder message
  "account_name": "Назва облікового запису",
  // button description
  "show_qr_code": "Показати QR код",
  // infomessage for the user
  "do_not_send_2": "Не відправляйте TRX з вашого власного гаманця або біржі на зазначену адресу облікового запису тест-мережі!",
  // subtitle - statistic information eg. 2 Bandwidth
  "bandwidth": "пропускна здатність",
  // subtitle - statistic information eg. 5 Balance
  "balance": "баланс",
  // subtitle - statistic information eg. 100 Tron Power
  "tron_power": "Tron Power",
  // title/headline of the table
  "transactions": "транзакції",
  // infomessage - no transfers have been made yet
  "no_transfers": "Переводи відсутні",
  // infomessage - no tokens present
  "no_tokens": "Токени відсутні",
  // subtitle - statistic information eg. 2  Free Bandwidth
  "free_bandwidth": "вільна пропускна здатність",
  // field name - expires
  "expires": "закінчується",
  // infomessage - receive trx eg. 10 trx have been added to your account!
  "have_been_added_to_your_account": "були додані до вашого облікового запису!",
  // infomessage - Testnet informessage - receive 10000 TRX for testing
  "information_message_1": "При розміщенні запиту на отримання TRX, Ви отримаєте 10000 TRX які Ви можете використати в тестовій мережі.",
  // infomessage - Testnet informessage - limitation
  "information_message_2": "Обмеження на запит TRX - 10 разів на один обліковий запис.",
  // button description - Request TRX for testing
  "request_trx_for_testing": "Запит TRX для тестування",
  // information - token balances
  "token_balances": "Баланси токенів",
  // tableinformation - row name - produced blocks
  "produced_blocks": "вироблено блоків",
  // tableinformation - row name - voters
  "voters": "виборці",
  // statusinformation -  progress
  "progress": "прогрес",
  // statusinformation - transaction
  "transactions_count": "{Транзакції, множина, одна {транзікція} інша {транзакції}}",
   // tableinformation - row name - issuer
  "issuer": "видавець",
  // tableinformation - row name - network
  "network": "мережа",
  // tableinformation - row name - current
  "current": "поточний",
  // button description to receive test trx
  "trx_received": "TRX отримано",
  // errormessage - TRX for testing temporarily unavailable
  "test_trx_temporarily_unavailable_message": "Тестові TRX тимчасово недоступні. Будь ласка спробуйте пізніше.",
  // errormessage - Not enough TRX to freeze
  "not_enough_trx": "Недостатньо TRX",
  "information_message_3": "Запит на отримання ТRX успішний. Якщо ви не отримали TRX, значить відсутні тестові TRX, які можливо отримати прямо зараз, і вам слід спробувати ще раз пізніше.",
  // address title -> receive trx - TRX address
  "send_to_following_address": "Надіслати на наступні адреси",

/*
##################################################################################
#                                                                                #
# account freeze                                                                 #
#                                                                                #
##################################################################################
*/
  // button description - to freeze trx
  "freeze": "заморозити",
  // button description - to unfreez trx
  "unfreeze": "розморозити",
  // infomessage - description
  "freeze_trx_least": "Вам потрібен як мінімум 1 TRX для заморозки",
  // errormessage - message text
  "unable_unfreeze_trx_message": "Неможливо розморозити TRX. Це може бути викликано тим, що мінімальний період заморожування ще не досягнуто.",
  // infomessage - text module 1
  "freeze_trx_premessage_0": `TRX можна заморозити/заблокувати, щоб отримати Tron Power та використати додаткові функції. Наприклад, з Tron Power ви можете `,
  // link - text module 1
  "freeze_trx_premessage_link": "голосувати за Супер-представників.",
  // infomessage - text module 2
  "freeze_trx_premessage_1": ` Заморожені токени "заблоковані" протягом 3 днів. Протягом цього періоду заморожі TRX не можливо продати. Після цього періоду ви можете розморозити і продавати TRX.`,
  // input field description
  "trx_amount": "Кількість TRX ",
  // infomessage - text module 1 - I confirm to freeze XXX trx for at least of 3 days
  "token_freeze_confirm_message_0": "Я підтверджую заморозку ",
  // infomessage - text module 2 - I confirm to freeze XXX trx for at least of 3 days
  "token_freeze_confirm_message_1": "мінімум на 3 дні",
  // table title - Frozen Supply
  "frozen_supply": "Заморожений Запас",
  "tokens_unfrozen": "Розморожені токени",
  "success_tokens_unfrozen_message": "Токени розморожені успішно",
  "unable_to_unfreeze": "Unable to unfreeze",
  "Unable_tokens_unfrozen_message": "Неможливо розморозити токени.",
  "tokens_frozen": "Токени заморожені",
  "successfully_frozen": "Заморожені успішно",
  "name_changed": "Ім'я змінено",
  "successfully_changed_name_to_message": "Ім'я змінено успішно на",
  "unable_to_rename_title": "Перейменування неможливе",
  "unable_to_rename_message": "Щось пішло не так в процесі оновлення назви Вашого облікового запису, спробуйте пізніше ще раз",
  "unfreeze_trx_confirm_message": "Ви дійсно бажаєте розморозити TRX?",
/*
##################################################################################
#                                                                                #
# account superdelegates                                                         #
#                                                                                #
##################################################################################
*/
  // button description - apply for delegate
  "apply_for_delegate": "подати заявку на делегата",
  // button description - Apply to be a Super Representative Candidate
  "apply_super_representative_candidate": "Подати заявку на кандидата у Супер-представники",
  // inputfield description - Homepage
  "your_personal_website_address": "адреса персонального вебсайту",
  // infomessage - predescription
  "apply_for_delegate_predescription":`Кожний тримач токенів має можливість стати Супер-представником ТРОН.
   Однак, щоб мережа та спільнота працювали більш ефективно, ми створили набір стандартів і правил для кандидатів, які мають право стати рекомендованими Супер-представниками. 
   Ми будемо просувати наших супер-представників задля збільшення їх шанси бути обраними. 
   Щотижня ми будемо оновлювати дані о супер-представниках`,
  // infomessage - description
  "apply_for_delegate_description": `
   Власники TRX можуть подати заявку, щоб стати Супер-представником, використовуючи функцію управління обліковим записом, а також проголосувати за кандидатів.
   Кожний обліковий запис може оновити поточні дані про виборців, а також дозволяє проголосувати за декількох кандидатів.
   Максимальна кількість голосів має бути меншою або дорівнює кількості користувачів TRX, які користувачі мають кожного разу.
   (Якщо у вас є певна кількість TRX, ви можете віддати менше або рівне цим TRX кількість голосів).
   Результат голосування буде розраховуватися на підставі остаточної інформації про виборців кожного рахунку в кожному
   циклі голосування, який триває з 00:00 до 24:00. Власники TRX з більшістю голосів стануть суперделегатами.
   Кожна транзакція, здійснена в мережі, повинна бути перевірена усіма Супер-представниками, які отримають за це бонуси.
   TRX не буде витрачатися в процесі голосування за Супер-представників.`,
  // errormessage - an unknown error occurred
  "unknown_error": "сталася невідома помилка",
  // confirm - message
  "representative_understand": "Я розумію як стати Представником TRON",
  // button description - create address and password
  "generate_account": "Натисніть, щоб створити адресу та пароль свого облікового запису",
  // confirm message - part 1
  "create_account_confirm_1": "Я розумію, що якщо я забуду/втрачу свій пароль, то ніколи не зможу отримати доступ до своїх активів",
  // confirm message - part 2
  "create_account_confirm_2": "Я розумію, що якщо я забуду/втрачу свій пароль, то ніхто не зможе допомогти мені відновити його",
  // confirm message - part 3
  "create_account_confirm_3": "Я написав свій пароль на папері",
  // confirm message - submitting the vote
  "vote_thanks": "Дякуємо за голосування!",
  "recent_transactions": "останні операції",
  "newest_account": "найновші облікові записи",
  "representatives": "представноки",
  "most_votes": "більшість голосів",
  "start_end_time": "Час Початку/Кінця",
  "scan_qr_code": "Проскануйте код з QR Code сканером",
  "receive_trx": "отримати TRX",
  "require_account_to_send": "Ви повинні увійти в систему для відправки монет",
  "require_account_to_receive": "Ви повинні увійти в систему для отримання монет",
  "successful_send": "Успішно відправлено!",
  "confirm_transaction": "підтвердити транзакцію",
  "last_confirmed": "Останній підтверджений",
  "trx_produced": "Транзакцій зроблено",
  "do_not_send_1": ""Не відправляйте TRX з вашого власного гаманця або біржі на зазначену адресу облікового запису тест-мережі!",
  // button description - Go to votelist
  "go_to_votelist": "До списку виборців",

/*
##################################################################################
#                                                                                #
# token creation formular                                                        #
#                                                                                #
##################################################################################
*/
  // description of an input field - Name of the token
  "name_of_the_token": "Ім'я токену",
  // longdescription - additional userinfo - Name of the token
  "token_message": "Ім'я для токену",
  // description of an input field - token Abbreviation
  "token_abbr": "Аббревіатура токену",
  // longdescription - additional userinfo - token Abbreviation
  "abbr_message": "Аббревіатура для токену",
  // field information - statistics - total supply of trx
  "total_supply": "всього токенів",
  // field information - issued token
  "issued_token": "випущено токенів",
  // button description - Create Token
  "create_token": "Створити токен",
  // description of an input field - Description
  "description": "Опис",
  // description of an input field -  Description URL
  "description_url": "Опис URL",
  // field information - Quote Token Amount
  "quote_token_amount": "Загальна кількість токенів",
  // field information - Base Token Amount
  "base_token_amount": "Базова кількість токенів",
  // statusmessage - Creating a token
  "creating_a_token": "Створення токена",
  // field information - available
  "available": "наявні",
  // title - Testnet
  "testnet": "Тестова мережа",
  "days_to_freeze": "Днів заморзки",
  "trx_token_fee_message": "1024 TRX необхідно для випуску нового токену",
  "trx_token_account_limit": "Ви можете створити тільки 1 токен для кожного облікового запису",
  "trx_token_wallet_requirement": "Вім потрідно відкрити гаманець, для створення токену",
  "invalid_address": "некоректна адреса",
  "insufficient_tokens": "Недостатньо токенів",
  "fill_a_valid_number": "Будь ласка, введіть коректний номер",
  "fill_a_valid_address": "Будь ласка, введіть коректну адресу",
  "make_another_transaction": "Здійсніть іншу транзакцію",
  "token_exchange_confirm": "Я підтверджую витрату {trxAmount} на розподіл токенов, і отримання {tokenAmount} токенів.",
  "An_unknown_error_occurred,_please_try_again_in_a_few_minutes": "Виникла невідома помилка, будь ласка, спробуйте ще раз через кілька хвилин",
  "An_error_occurred": "Виникла помилка",
  "create_a_token": "Створити токен",
  "not_started_yet": "Ще не почалося",
  "participated": "Ви успішно взяли участь!",
  "participated_error": "Виникла помилка",

/*
##################################################################################
#                                                                                #
# token participate                                                              #
#                                                                                #
##################################################################################
*/
  // messagedialog - title
  "buy_confirm_message_0": "Ви впевненні?",
  // messagedialog - maintext
  "how_much_buy_message": "Яку кількість токенів ви бажаєте купити?",
  // infomessage - text module 1 - Are you sure you want to buy 1 <Tokenname> for 1 TRX
  "buy_confirm_message_1": "Ви дійсно бажаєте купити",
  // infomessage - text module 1 - Are you sure you want to buy 1 <Tokenname> for 1 TRX
  "for": "для",

/*
##################################################################################
#                                                                                #
# global messages                                                                #
#                                                                                #
##################################################################################
*/
  // error message - incorrect trx address
  "address_warning": "Введіть тільки дійсну адресу гаманця TRON. Неправильні адреси можуть призвести до втрати TRX.",
  // statusmessage - search for address or URL
  "search_address_or_url": "Пошук за адресою або URL",
  // statusmessage
  "the_lunch_test": "Запуск тестової мережі націлений на тестування всіх функцій нашого блокчейн-оглядача і гаманця.",
  // statusmessage
  "please_keep_in_mind": "Будь ласка, майте на увазі, що ваша адреса облікового запису зареєстрована тільки для використання 
   в тестовій мережі, не відправляйте TRX з вашого власного гаманця або біржі на адресу облікового запису в тестовій мережі.",
  // statusmessage - title
  "tron_foundation": "TRON Foundation",
  // statusmessage
  "trx_for_testing": "TRX для тестування буде відправлено до вашого тестового облікового запису після успішного застосування через керування обліковим записом.",
  // statusmessage
  "dear_users": "Шановні користувачі,",
  // field information  - fin
  "finished": "Завершено",
  // field information  - token
  "token": "токен",
  // field information  - website url
  "url": "url",
  // infomessage - loggin is required
  "need_to_login": "Ви повинні увійти в систему, щоб отримати доступ до сторінки облікового запису",
  // confirm message - Thanks for applying!
  "thanks_for_applying": "Дякуємо за подачу заявки!",
  // errormessage - To many votes
  "to_much_votes": "Велика кількість голосів",
  // errormessage - No TRX remaining
  "no_trx_remaining": "TRX не залишилося",
  // statusmessage - Produced by TRX address
  "produced_by": "Вироблено {witnessAddress}",
   // infomessage .. Show XXX more
  "show_more": "Показати {countriesLength} більше",
  // infomessage - vote guide
  "vote_guide_message": `Використовуйте TRX для голосування за Супер-Представників.
   За кожен TRX який є в обліковому записі, Ви отримуєте один голос для голосування.
   TRX НЕ будуть витрачатися. Ви можете голосувати скільки завгодно раз за кількох бажаних представників.
   Фінальні голоси будуть підраховані в 24 години і список делегатів буде оновлено.`,
  // infofield
  "search_address": "Пошук за адресою",
  // infofield - Token Transactions
  "token_transactions": "Транзакції токенів",
  // infofield - Token Holders
  "token_holders": "Тримачі токенів",
  // infofield - Number of Transfers
  "nr_of_Transfers": "Кількість переказів",
  // errormessage -> login required
  "not_signed_in": "Ви повинні увійти в систему для використання цього функціоналу",
  // statusmessage - Loading Map
  "loading_map": "Завантаження карти",
  // statusmessage - loading Accounts
  "loading_accounts": "завантаження облікового запису",
  // table - row title - quantity
  "quantity": "кількість",
  // table - row title - Percentage
  "percentage": "Відсоток",
  // statusmessage - loading token
  "loading_token": "Завантаження токену",

/*
##################################################################################
#                                                                                #
# transaction information                                                        #
#                                                                                #
##################################################################################
*/
  // statusmessage - No transactions found
  "no_transactions_found": "Транзакції не знайдені",
  // statusmessage - No tokens found
  "no_tokens_found": "Токени не знайдені",
  // statusmessage - No blocks found
  "no_blocks_found": "Блоки не знайдені",
  // statusmessage - No votes found
  "no_votes_found": "Голоси не знайдені",
  // statusmessage - No voters found
  "no_voters_found": "Голосуючі не знайдені",
  // statusmessage - Waiting for transactions ... still waiting
  "waiting_for_transactions": "В очікуванні тринзакції",
  // statusmessage - Loading Address ... still waiting
  "loading_address": "Завантаження адресів",

/*
##################################################################################
#                                                                                #
# token creation - default messages                                              #
#                                                                                #
##################################################################################
*/
  // button description - details
  "details": "деталі",
  // button description - Issue a Token
  "issue_a_token": "Випустити токен",
  // table - row name - Issue Token
  "issue_token": "Випустити токен",
  // table - row name - token name
  "token_name": "ім'я токену",
  // table - row name - Total issued
  "total_issued": "Всього видано",
  // table - row name - Registered
  "registered": "Зареєстровано",
  // table - row name - Abbreviations
  "abbreviation": "Абревіатури",
  // title - Exchange Rate
  "exchange_rate": "Курс обміну",
  // table - row name - Token Price
  "token_price": "Ціна токену",
  // usermessage - total amount of tokens
  "supply_message": "Загальна кількість токенов, які будуть в обігу",
  // field description - short description
  "description_message": "Короткий опис призначення токену",
  // field description - website url
  "url_message": "Веб сайт, де користувачі можуть знайти більше інформації про токен",
  // usermessage - Token
  "exchange_rate_message_0": "Вкажіть ціну одного токена, визначивши, скільки токенов учасник отримає за кожен витрачений TRX.",
  // usermessage - text part 1 - Participants will receive 20 XXX for every 10 TRX
  "exchange_rate_message_1": "Учасник отримає",
  // usermessage - text part 2 - Participants will receive 20 XXX for every 10 TRX
  "exchange_rate_message_2": "за кожен/кожні",
  // usermessage - text part 3 - Participants will receive 20 XXX for every 10 TRX
  "exchange_rate_message_3": "TRX",
  // usermessage - text part 1 - Participation Message
  "participation_message_0": "Вкажіть період участі, в якому будуть випущені токени. Протягом періоду участі користувачі можуть обміняти TRX на ",
  // usermessage - text part 2 - Participation Message
  "participation_message_1": " токени.",
  // usermessage - text part 1 - frozen supply message
  "frozen_supply_message_0": `Частина обсягу може бути заморожена. Обсяг може бути вказаний і буде заморожений як мінімум на 1 день.. Заморожений обсяг може бути вручну розморожений після дати початку + заморожені
  дні були досягнуті. Заморожений обсяг не потрібен.`,
  // statusmessage - Token successfully issued
  "token_issued_successfully": "Токен успішно випущений",
  // title - participation
  "participation": "учасник",
  // description - date/time pannel - Start Date
  "start_date": "Дата початку",
  // description - date/time pannel - End Date
  "end_date": "Дата кінця",
  // confirm message - token spend
  "token_spend_confirm": ""Я підтверджую, що створення загального обсягу токенов дорівнює в цілому 1024 TRX",
  // userinfomation - token issue guide message - part 1
  "token_issue_guide_message_1": `Випуск токена на Протоколі Tron можливо
    для кожного, хто має хоча б 1024 TRX на своєму акаунті..`,
  // userinfomation - token issue guide message - part 2
  "token_issue_guide_message_2":`Коли токен випущений, це повинно бути відображено на сторінці огляду токена. 
   Потім користувачі можуть брати участь під час періоду участі і обміну TRX на токени.`,
  // userinfomation - token issue guide message - part 3
  "token_issue_guide_message_3":`Після випуску токена ваш аккаунт отримає кількість токенов, що дорівнює загальному обсягу.
    Коли інші користувачі обмінюють свої TRX на токени, то токени будуть списуватися з Вашого облікового запису і Ви будете
    отримувати TRX, рівні зазначеному обмінному курсу.`,

/*
##################################################################################
#                                                                                #
# token creation - error messages                                                #
#                                                                                #
##################################################################################
*/
  // errormessage - startdate>= enddate
  "date_error": "Дата закінчення раніше або збігається з датою початку",
  // errormessage - an token name is required
  "no_name_error": "Потрібно ім'я",
  // errormessage - total supply > 0
  "no_supply_error": "Загальний обсяг повинен бути рівний хоча б 1",
  // errormessage - token amount must be at least 1
  "coin_value_error": "Кількість токенов має дорівнювати хоча б 1",
  // errormessage - The amount of TRX per coin must be at least 1
  "tron_value_error": "Кількість TRX за монету має дорівнювати хоча б 1",
  // errormessage - startdate is invalid
  "invalid_starttime_error": "Надана ​​початкова дата не коректна",
  // errormessage - enddate is invalid
  "invalid_endtime_error": "Надана ​​кінцева дата не коректна",
  // errormessage - en tokendescription is required
  "no_description_error": "Опис необхідний",
  // errormessage - en URL (website) is required
  "no_url_error": "Web посилання необхідне",
  // errormessage - startdate < now
  "past_starttime_error": "Початкова дата в минулому",
  // statusmessage - no transactions available
  "no_transactions": "Немає транзакцій",

/*
##################################################################################
#                                                                                #
# representatives section                                                        #
#                                                                                #
##################################################################################
*/
  // statistic dialog - Highest Productivity eg. tron node XXX Highest Productivity
  "highest_productivity": "Найвища продуктивність",
  // statistic dialog - Highest Productivity eg. tron node YYY Lowest Productivity
  "lowest_productivity": "Найнижча продуктивність",
  // title name - SR
  "Super Representatives": "Супер-представники",
  // title name - SRC
  "Super Representative Candidates": "Кандидати у Супер-представники",
  // statusmessage -  loding Representatives informations
  "loading_representatives": "Завантаження представників",
  // errormessage - not a valid SR address
  "address_not_super_representative": "Ця адреса не є адресою Супер-представника",
  // errormessage - unable to load SR page
  "unable_load_representatives_page_message": "Не вдається завантажити сторінку, це може статися, якщо адреса недійсна, адреса не є адресою представника, або представник ще не налаштовував цю сторінку",

/*
##################################################################################
#                                                                                #
# markets section                                                                #
#                                                                                #
##################################################################################
*/
  // statistic information (Average Price in USD)
  "average_price_usd": "Середня ціна в USD",
  // statistic information (Average Volume in USD)
  "average_volume_usd": "Середній об'єм USD",
  // statistic information (Trade Volume)
  "Trade Volume": "Торговий Об'єм",
  // table - row titel - rank of exchanges (trading volume)
  "rank": "рейтинг",
  // table - row titel - pair (trading pair TRX/USD)
  "pair": "пара",
  // table - row titel - Volume (trading volume)
  "volume": "Об'єм",

/*
##################################################################################
#                                                                                #
# votes section                                                                  #
#                                                                                #
##################################################################################
*/
  // statistic information eg. 02:00 ..Next Round
  "next_round": "Наступний раунд",
  // statistic information eg.23982829432 Total Votes
  "total_votes": "Всього голосів",
  // statistic information eg. Most Ranks Gained This Round .. SR TEST
  "most_ranks": "Вищий рейтинг за раунд",
  // button description - to View Live Ranking
  "view_live_ranking": "Подивитися рейтинг наживу",
  // button description - to Open Team Page
  "open_team_page": "Відкрити сторінку у команди",
  // userinformation message - text section 1
  "warning_votes": "Хоча б 1 Tron Power потрібно для початку голосування. Tron Power досягається заморожуванням TRX на",
  // userinformation message - HyperLink - text section 2
  "account_page": "Сторінці Облікового запису",
  // loading message - to Loading Votes
  "loading_votes": "Завантаження голосів",
  // chart title - 3 Days Ranking
  "3_day_ranking": "Рейтинг за 3 дні",
  // userinformation message 2 - title
  "live_ranking": "Рейтинг наживу",
  // userinformation message 2 - description
  "live_ranking_msg": "Оновлюється кожні 15 секунд. Нові голоси можуть бути прийняті до 1-2 хвилини до підрахунку голосів",
  // table - row title - Candidate
  "candidate": "Кандидат",
  // table - row title - Current Votes
  "current_votes": "Поточні голоси",
  // button description - to Click here to Start Voting
  "click_to_start_voting": "Натисніть щоб розпочати голосування",
  // infomessage how many votes are available eg. 20 Votes Remaining
  "votes_remaining_message": "Голосів Лишилось",
  // errormessage - Open wallet to start voting
  "open_wallet_start_voting_message": "Відкрийте гаманець, щоб розпочати голосування",
  // infomessage - submitting vote
  "thanks_submitting_vote_message": "Дякуємо, що подали свій голос!",
  // errormessage - You need at least 1 TRX to be able to vote
  "need_min_trx_to_vote_message": "Вам потрібно мати принаймні 1 TRX, для голосування",
  // errormessage - voting - You spend to much votes
  "to_much_votes_massage": "Ви витрачаєте багато голосів!",
  // statusmessage - All votes are used!
  "all_votes_are_used_message": "Всі голоси використані!",
  // statusmessage - title - Thank you for voting!
  "submissing_vote_message_title": "Дякуємо за голосування!",
  // statusmessage - description - part 1
  "submissing_vote_message_0": "Ваші голоси успішно зараховані, вони набируть чинності після початку наступного циклу голосування.",
  // statusmessage - description - part 2
  "submissing_vote_message_1": "Ви можете розподілити свої голоси будь-коли, коли захочете",
  // errormessage - voting
  "submitting_vote_error_message": "Щось сталося не дуже добре під час подання ваших голосів. Будь-ласка спробуйте пізніше.",

/*
##################################################################################
#                                                                                #
# transaction Viewer                                                             #
#                                                                                #
##################################################################################
*/
  "info_tx_viewer": "Тут ви можете вставити номер транзакції, щоб перевірити її транзакції. Транзакція може транслюватися в мережі",
  "load_tx": "Завантаження транзакції",
  "tx_qrcode": "QR код транзакції",
  "load_tx_qrcode": "Завантажити транзакцію з QR Code",
  "transaction_load_error": "Помилка завантаження транзакції",
  "transaction_load_error_message": "Щось сталося не дуже добре під час завантаження транзакції. Впевніться що HEX має корректний формат",
  "transaction_success_message": "Транзакція успішно передана в мережу.",
  "transaction_success": "Транзакція успішна",
  "transaction_error_message": "Під час спроби транслювати транзакцію сталася помилка",
  "transaction_error": "Помилка транзакції",
  "confirm_transaction_message": "Ви впевненні, що Ви хочете відправити транзакцію?",
  "broadcast_transaction_to_network": "Передача транзакції в мережу",

/*
##################################################################################
#                                                                                #
# tools node tester                                                              #
#                                                                                #
##################################################################################
*/
  // field descritionp - enter a valid ip address
  "node_tester_msg": "Вставте IP адресу Вашого вузла, щоб протестувати GRPC падключення",
  // button description - to stop the test
  "node_tester_stop": "Зупинити тестування",
  // button description - to start the test
  "node_tester_test": "Тестування GRPC",
  // tableinformation - row title
  "node_tester_rt": "Час відповіді",
  // tableinformation - row title
  "confirmed_block": "Підтверджений блок",
  // status dialog ... to loding the test result
  "loading": "завантаження...",

/*
##################################################################################
#                                                                                #
# tools scanner                                                                  #
#                                                                                #
##################################################################################
*/
  // errormessage - No webcam found
  "no_webcam_found": "Вебкамера не знайдена",
  // errormessage - Error while trying to enable webcam.
  "trying_enable_webcam_message_0": "Помилка під час спроби ввімкнути веб-камеру.",
  // errormessage - Make sure camera permissions are enabled.
  "trying_enable_webcam_message_1": "Переконайтеся, що камера має дозвіл на увімкнення.",

/*
##################################################################################
#                                                                                #
# help section                                                                   #
#                                                                                #
##################################################################################
*/
  // navigation bar - help - hyperlink - to get informations about tron
  "what_is_tron": "Що таке TRON",
  // navigation bar - help - hyperlink - to get
  "tron_explorer_api": "Tron Explorer API",
  // navigation bar - help - hyperlink - to get informations about the TRON Architecture
  "tron_architechure": "TRON Архітектура",
  // navigation bar - help - hyperlink - to get the TRON Protobuf Documentation
  "tron_protobuf_doc": "TRON Protobuf документація",
  // navigation bar - help - hyperlink - to Submit a bug / suggestion
  "report_an_error": "Надіслати помилку / пропозицію
",

/*
##################################################################################
#                                                                                #
# wallet section                                                                 #
#                                                                                #
##################################################################################
*/
  // button description - to open a new wallet
  "open_wallet": "Відкрити гаманець",
  // input field description to enter the private key for the authentication
  "private_key": "Закритий ключ",
  // description to select the keystore file for the authentication
  "keystore_file": "Файл ключа",
  // button description - select the keystore file
  "select_file": "Виберіь файл",
  // button description - Login with a mobile device
  "login_mobile": "Вхід за допомогою мобільного пристрою",
  // button description - create wallet
  "create_wallet": "створити гаманець",
  // errormessage - no wallet available - No open wallet to view
  "no_open_wallet": "Немає відкритого гаманця для перегляду",
  // wizzard dialog - create new wallet - title
  "new_wallet": "Створити новий гаманець",
  // wizzard dialog - create new wallet - password information message 1
  "password_encr_key_message_0": "Цей пароль закодує Ваш закритий ключ. Це не теж саме що і seed, для генерації Ваших ключів.",
  // wizzard dialog - create new wallet - password information message 1
  "password_encr_key_message_1": "Вам знадобляться цей пароль і ваш приватний ключ для розблокування гаманця.",
  // wizzard dialog - create new wallet - password field description
  "strong_password_info": "Потрібно використовувати складний пароль",
  // wizzard dialog - create new wallet - title
  "save_keystore_file": "Зберегти файл ключа",
  // wizzard dialog - create new wallet - button description to download the keystore file
  "download_keystore_file": "Завантажити файл ключа",
  // wizzard dialog - create new wallet - userinformation 1 prefix
  "do_not_lose_it": "Не згубіть його!",
  // wizzard dialog - create new wallet - userinformation 1 text
  "do_not_lose_it_message_0": "Tron Foundation не зможе допомогти Вам його відновити.",
  // wizzard dialog - create new wallet - userinformation 2 prefix
  "do_not_share_it": "Не діліться ним!",
  // wizzard dialog - create new wallet - userinformation 2 text
  "do_not_share_it_message_0": "Ваші кошти можуть бути викрадені, якщо ви використуєте цей файл на зловмисному сайті",
  // wizzard dialog - create new wallet - userinformation 3 prefix
  "make_a_backup": "Створіть резервну копію!",
  // wizzard dialog - create new wallet - userinformation 3 text
  "make_a_backup_message_0": "Про всяк випадок, якщо Ваш ноутбук спалахне.",
  // wizzard dialog - create new wallet - inputfield title
  "save_private_key": "Збережіть закритий ключ",
  // wizzard dialog - create new wallet - button description to print an paper wallet
  "print_paper_wallet": "Роздрукуйте паперовий гаманець",
  // wizzard dialog - create new wallet - statusmessage 1
  "new_wallet_ready_message": "Ваш гаманець готовий",
  // wizzard dialog - create new wallet - button description
  "go_to_account_page": "До сторінки облікового запису",

};
