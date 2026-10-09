# Morteza Pazhoum

Software developer building backend systems, AI applications, machine learning solutions, and modern web platforms.

Computer Science student at K. N. Toosi University of Technology. The repositories below are systems I can walk through end to end.

## About Me

I work on software that has to stay correct under real constraints: money that cannot be double-spent, answers that must cite a source, and safety alerts a family can trust.

Most of the work is backend development in Python and Node.js, with machine learning and retrieval where the data is local and the result has to be inspectable. Beside that I ship desktop and web interfaces when the product needs them. I would rather finish a small system with a clear invariant than a demo that only looks finished.

## Featured Projects

### [safestep](https://github.com/MortezaPZ/safestep)

Safety and location tracking for someone who wants to go out independently, and for the family that needs a reliable alert when something goes wrong.

**Stack:** Node.js, Express, PostgreSQL, Flutter, Socket.IO

Live location, geofences with hysteresis, fall detection, SOS, and a web console sit in one product. The person can always see who is watching and can stop sharing.

### [PersianLedger](https://github.com/MortezaPZ/PersianLedger)

A desktop multi-currency ledger. Each currency stays in double-entry books, dates are Jalali, and posted documents are not quietly rewritten.

**Stack:** Python, PySide6, SQLAlchemy, SQLite, PostgreSQL

Interesting because the accounting rules are enforced in the application: each currency must balance, attachments travel with the books, and the same desktop client can move onto an office PostgreSQL server.

### [rag-document-assistant](https://github.com/MortezaPZ/rag-document-assistant)

Ask a question about your own documents and get an answer that points back to the passage it came from.

**Stack:** Python, FastAPI, sentence-transformers, SQLite

The default path runs locally. An optional hosted model key is only used when you configure one on purpose.

### [eitaa-forward-bot](https://github.com/MortezaPZ/eitaa-forward-bot)

Forwards posts from an Eitaa channel to managed groups through a durable queue, with delay, rate limits, and restart-safe delivery.

**Stack:** Python, SQLite, FastAPI admin panel, Windows web transport

Interesting because delivery is treated as a queue problem, not a one-shot script: failed sends retry, duplicates do not go out twice, and the Windows Edge session path is documented separately from the legacy HTTP transport.

### [gemopt](https://github.com/MortezaPZ/gemopt)

A stone-cut optimizer. It varies cut parameters, traces light through each candidate, scores the result against a reference photo, and exports the chosen cut for 3ds Max.

**Stack:** Python, NumPy, SciPy, Pillow, 3ds Max export

Interesting because the search, the optics, and the Max exchange file share one parameter set instead of three hand-edited pipelines.

### [customer-churn-analytics](https://github.com/MortezaPZ/customer-churn-analytics)

Upload a customer CSV, train a churn model, and see who is likely to leave and which fields drove that score.

**Stack:** Django REST Framework, scikit-learn, Angular

The holdout comparison is in the repository. The dashboard is for acting on risk segments, not for a single accuracy slide.

## Technical Skills

Technologies the repositories actually use:

- Python
- TypeScript and JavaScript
- Node.js
- Django and FastAPI
- Angular, React, and Next.js
- Flutter
- PostgreSQL and SQLite
- Machine learning with scikit-learn and PyTorch
- LLM and RAG over local documents
- ASP.NET Core and SignalR
- Docker

## Contact

- GitHub: [MortezaPZ](https://github.com/MortezaPZ)
- Email: mortezapzhm@gmail.com
