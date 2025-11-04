- The trick to adding these back in is that, by default, they are passed session_options when added (including the session key), so you can't just add a session_store.rb initializer, add use ActionDispatch::Session::CookieStore and have sessions functioning as usual.

- with only one billion dollars we have improved swebench performance by a full 3%. after 500m on compute and 500m on data sadly there’s no money remaining to improve the benchmark itself. but worry not as we have ten billion planned for next time
 
