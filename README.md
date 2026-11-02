# SpendWise

## Project Goal

A Python expense tracker that helps users organize transactions, visualize spending, and manage monthly budgets.

## MVP Features

- Upload CSV transactions
- Categorize expenses manually
- Save and load transactions
- View monthly spending charts
- Set and track monthly budgets

Transaction uploads will use CSV files containing `date`, `description`, and `amount` columns, with positive amounts representing expenses.

## Future Features

- Automatic expense categorization
- Recurring expense detection
- Multi-month spending comparisons
- Exportable spending reports

## Tech Stack

- Python 3
- Streamlit for the user interface
- Pandas for CSV processing
- Plotly for interactive charts
- CSV and JSON for local data storage
- Git and GitHub for version control

## Documentation

- [Eisenhower Matrix](docs/eisenhower-matrix.pdf)
- [System Diagram](docs/system-diagram.png)

## Project Structure

- `src/` - Application logic
- `data/` - Fictional sample transactions
- `tests/` - Application tests
- `docs/` - Project planning documents

## Development Plan

1. Set up the repository and Python environment.
2. Build the Streamlit dashboard.
3. Implement CSV uploads and validation.
4. Implement expense categorization.
5. Add local transaction storage and duplicate prevention.
6. Build monthly spending analytics and charts.
7. Implement monthly budget tracking.
8. Test, debug, and finalize documentation.

## Project Status

Planning and initial repository setup. The MVP will be implemented incrementally over the coming weeks.
