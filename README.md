# Productivity Tracker CLI 🚀

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

A command-line tool to track and visualize personal productivity metrics. Perfect for students and professionals to monitor time allocation across different activities.

## Features ✨

- 📝 Log activities with categories and duration
- 📊 Generate daily/weekly reports
- 📈 Create visual charts (pie & bar charts)
- 🔒 Local data storage (JSON format)
- ⚡ Simple CLI interface

## Installation 💻

```bash
# Clone repository
git clone https://github.com/yourusername/productivity-tracker.git
cd productivity-tracker

# Install dependencies
pip install -r requirements.txt

# Install package
python setup.py install
```

## Usage 🛠️

**Log an activity:**
```bash
productivity-tracker add study 2.5 -n "MLH Fellowship application work"
```

**Generate 7-day report:**
```bash
productivity-tracker report --days 7
```

**Create visualization:**
```bash
productivity-tracker visualize --output my_report.png
```

## Example Output 📊

![Sample Productivity Chart](sample_chart.png)

## Tech Stack 🧰

- Python 3.8+
- argparse for CLI interface
- matplotlib for visualization
- JSON for local data storage

## Contributing 🤝

Contributions welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
