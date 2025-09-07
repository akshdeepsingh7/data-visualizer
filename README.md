# Interactive Data Visualizer

A modern, responsive web application that transforms CSV data into beautiful, interactive charts. Built with vanilla JavaScript, Chart.js, and PapaParse for fast and reliable data visualization.

![Data Visualizer Screenshot](https://via.placeholder.com/800x400/4f46e5/ffffff?text=Interactive+Data+Visualizer)

## ✨ Features

- **Multiple Chart Types**: Bar charts, line charts, pie charts, and scatter plots
- **Dual Input Methods**: Upload CSV files or paste data directly
- **Real-time Preview**: Instant chart generation and updates
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Interactive Charts**: Hover tooltips and clickable legends
- **Modern UI**: Clean, professional interface with smooth animations
- **No Backend Required**: Runs entirely in the browser

## 🚀 Quick Start

1. **Download** the HTML file to your computer
2. **Open** it in any modern web browser
3. **Upload** a CSV file or use the sample data provided
4. **Select** your chart type and data columns
5. **Click** "Visualize Data" to generate your chart

## 📊 Supported Chart Types

### Bar Chart
Perfect for comparing categories or showing changes over time.
- **Use case**: Sales by region, monthly revenue
- **Data**: Categories (labels) + numeric values

### Line Chart
Ideal for showing trends and changes over time.
- **Use case**: Stock prices, website traffic, temperature changes
- **Data**: Time series or sequential data

### Pie Chart
Great for showing proportions and percentages.
- **Use case**: Market share, budget allocation, survey results
- **Data**: Categories + their respective values

### Scatter Plot
Excellent for showing relationships between two numeric variables.
- **Use case**: Height vs weight, advertising spend vs sales
- **Data**: Two numeric columns

## 📝 Data Format Requirements

### CSV Structure
Your CSV data should have:
- **Header row** with column names
- **Consistent data types** within each column
- **No empty rows** (they'll be automatically skipped)

### Example CSV Format
```csv
Year,Revenue,Expenses,Profit
2018,1000,600,400
2019,1150,650,500
2020,950,700,250
2021,1300,750,550
2022,1500,850,650
2023,1700,950,750
```

### Supported Data Types
- **Text/Categories**: Names, dates, labels
- **Numbers**: Integers, decimals (use dots for decimal points)
- **Mixed columns**: The app will auto-detect the appropriate data type

## 🛠️ Technical Details

### Dependencies
- **Chart.js**: Modern charting library for interactive visualizations
- **PapaParse**: Robust CSV parsing library
- **Inter Font**: Clean, professional typography
- **Vanilla JavaScript**: No framework dependencies

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

### Performance
- Handles datasets up to **10,000 rows** smoothly
- Real-time parsing and chart updates
- Optimized rendering with Chart.js

## 🎨 Customization Options

### Chart Appearance
- **Automatic color generation** for visual appeal
- **Responsive sizing** that adapts to container
- **Professional styling** with consistent branding
- **Hover effects** and interactive elements

### User Interface
- **Clean, modern design** following current UI trends
- **Intuitive workflow** with numbered steps
- **Helpful placeholders** and guidance text
- **Error handling** with user-friendly messages

## 📱 Responsive Design

The application automatically adapts to different screen sizes:
- **Desktop**: Side-by-side layout with controls and visualization
- **Tablet**: Stacked layout with full-width components
- **Mobile**: Optimized for touch interaction and readability

## 🔧 Usage Tips

### Best Practices
1. **Clean your data** before importing (remove empty rows/columns)
2. **Use descriptive column names** for better chart labels
3. **Check data types** - ensure numeric columns contain only numbers
4. **Start simple** - try bar or line charts before complex visualizations

### Troubleshooting
- **Chart not appearing?** Check that you've selected valid columns
- **Data not parsing?** Ensure your CSV has proper headers and formatting
- **Colors look off?** Refresh the page to regenerate the color scheme
- **Performance issues?** Try reducing your dataset size

## 📋 Sample Datasets

Try these example datasets to get started:

### Sales Data
```csv
Month,Sales,Target
January,15000,12000
February,18000,15000
March,12000,14000
April,22000,18000
```

### Survey Results
```csv
Category,Responses
Very Satisfied,45
Satisfied,38
Neutral,12
Dissatisfied,5
```

## 🆘 Support

If you encounter any issues:
1. Check the browser console for error messages
2. Verify your CSV data format matches the examples
3. Ensure you're using a supported browser
4. Try refreshing the page and re-uploading your data

---

**Made with ❤️ for data visualization enthusiasts**
