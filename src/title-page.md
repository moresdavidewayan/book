# The Rust Programming Language

*di Steve Klabnik e Carol Nichols, con i contributi dalla Community di Rust*

Questa versione del testo presume tu stia utilizzando Rust 1.49 o superiore con
`edition="2018"` nel file *Cargo.toml* di tutti i progetti che usano il lessico dell' Edizione 2018 di Rust. Leggi la [sezione del Capitolo 1 "Installazione"][install]<!-- ignore -->
per installare o aggiornare Rust, e leggi la nuova [Appendice E][editions]<!-- ignore
--> per informazioni sulle edizioni.
L' Edizione 2018 del linguaggio Rust include diversi miglioramenti che
rendono Rust più comodo e facile da apprendere. Questa riedizione del libro
contiene diversi cambiamenti per riflettere questi miglioramenti:

- Capitolo 7, “Gestione dei Progetti in crescita con Pacchetti, Crates e Moduli,”
  è stata qusi del tutto riscritta. Il sistema dei moduli e il modo in cui vengono gestite le path nell' Edizione del 2018 sono state rese più uniformi.
- Il Capitolo 10 ha delle nuove sezioni intitolate “Tratti come Parametri” e “Ritornare Tipi che Implementano i Tratti” che spiegano la nuova sintassi `impl Trait`.
- Il Capitolo 11 ha una nuova sezione intitolata “Usare `Result<T, E>` nei Test” che spiega come scrivere meno test che utilizzino l' operatore `?`.
- The “Advanced Lifetimes” section in Capitolo 19 was removed because compiler
  improvements have made the constructs in that section even rarer.
- The previous Appendix D, “Macros,” has been expanded to include procedural
  macros and was moved to the “Macros” section in o 19.
- Appendix A, “Keywords,” also explains the new raw identifiers feature that
  enables code written in the 2015 Edition and the 2018 Edition to interoperate.
- Appendix D is now titled “Useful Development Tools” and covers recently
  released tools that help you write Rust code.
- We fixed a number of small errors and imprecise wording throughout the book.
  Thank you to the readers who reported them!
  Note that any code in earlier iterations of *The Rust Programming Language*
  that compiled will continue to compile without `edition="2018"` in the
  project’s *Cargo.toml*, even as you update the Rust compiler version you’re
  using. That’s Rust’s backward compatibility guarantees at work!
  Il formato HTML è disponibile online su
  [https://doc.rust-lang.org/stable/book/](https://doc.rust-lang.org/stable/book/)
  e offline con l'installazione di Rust fatta con `rustup`; esegui `rustup docs
  --book` per aprire.
  Questo libro è disponibile in [formato cartaceo ed ebook dalla No Starch
  Press][nsprust].

[install]: ch01-01-installation.html
[editions]: appendix-05-editions.html
[nsprust]: https://nostarch.com/rust
