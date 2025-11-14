# 📊 CHIN4101 Topical research in Chinese language and literature Visualizations

**Research Focus: Analysis of Chinese Character Variants Across Dynasties**

A comprehensive data visualization project analyzing the historical evolution of Chinese character variants (特别是"們"字及其变体) across different dynasties. This repository contains processed datasets and generated visualizations from historical Chinese text analysis.

Aims to support research on the historical evolution of "們" based on documented linguistic evidence:

- **唐代**: 文献里有"弭／彌""偉"与"們"用法相同
- **宋代**: "們"是最后出现的，还作"懣""滿""瞞""門"等
- **元代**: 多写作"每"
- **明代**: 中叶"們"才又多起来

## 🎯 Project Overview

This project presents the visualization and analysis outputs from a comprehensive study of Chinese character evolution across multiple historical dynasties, focusing on frequency patterns, temporal evolution, and dynasty-level comparative analysis.

### 📊 Key Research Components

- **Dynasty-Level Analysis**: Comprehensive examination of character variant usage within specific historical periods
- **Temporal Evolution Tracking**: Chronological visualization of character frequency changes over time
- **Book-Level Granularity**: Individual text analysis with author and title metadata
- **Optimized Visualizations**: Curated visualizations focusing on statistically significant patterns

## 📁 Repository Structure

```
CHIN4101_Visualizations/
├── 📂 dynasty_level_analysis_20251029/          # Raw dynasty-specific analysis results
│   ├── 📂 dynasty_level_analysis_complete_dataset/   # Comprehensive aggregated data
│   │   ├── 📄 frequency_evolution_data.json           # Master frequency evolution dataset
│   │   ├── 📄 book_variant_matrix_with_authors.csv    # Book-level variant frequency matrix
│   │   ├── 📄 dynasty_variant_summary.csv             # Dynasty-level aggregated summary
│   │   ├── 📄 author_variant_analysis.csv             # Author-based analysis
│   │   └── 📄 book_catalog_with_authors.csv           # Complete book catalog with metadata
│   ├── 📂 dynasty_元/                          # Yuan Dynasty (元代) analysis
│   ├── 📂 dynasty_唐/                          # Tang Dynasty (唐代) analysis
│   ├── 📂 dynasty_宋/                          # Song Dynasty (宋代) analysis
│   ├── 📂 dynasty_明/                          # Ming Dynasty (明代) analysis
│   ├── 📂 dynasty_清/                          # Qing Dynasty (清代) analysis
│   ├── 📂 dynasty_北宋/                        # Northern Song (北宋) analysis
│   ├── 📂 dynasty_南宋/                        # Southern Song (南宋) analysis
│   ├── 📂 dynasty_元初期/                      # Early Yuan (元初期) analysis
│   ├── 📂 dynasty_唐初期/                      # Early Tang (唐初期) analysis
│   ├── 📂 dynasty_明初期/                      # Early Ming (明初期) analysis
│   └── 📂 dynasty_北宋後期/                    # Late Northern Song (北宋後期) analysis
│
├── 📂 book_level_evolution_timeline_20251029/   # Timeline-based evolution analysis
│   ├── 📂 csv/                                 # Raw data exports
│   ├── 📂 html/                                # Interactive timeline visualizations
│   └── 📂 png/                                 # Static timeline images
│
├── 📂 optimized_top_n_books_dynasty_level_analysis/  # Curated top-performing visualizations
│   ├── 📄 README.md                           # Optimization methodology documentation
│   ├── 📄 dynasty_summary_dashboard.html      # Cross-dynasty comparison dashboard
│   ├── 📂 dynasty_元/                         # Optimized Yuan Dynasty visualizations
│   ├── 📂 dynasty_唐/                         # Optimized Tang Dynasty visualizations
│   ├── 📂 dynasty_宋/                         # Optimized Song Dynasty visualizations
│   ├── 📂 dynasty_明/                         # Optimized Ming Dynasty visualizations
│   ├── 📂 dynasty_清/                         # Optimized Qing Dynasty visualizations
│   └── [other dynasty directories...]
│
└── 📂 period_analysis_20251027/                # Period-based comparative analysis
    └── [dynasty-specific analysis directories]
```

## 🔍 Dataset Components

### Core Datasets

#### 1. **frequency_evolution_data.json**
- **Purpose**: Master dataset containing frequency evolution patterns
- **Content**: Character variant frequencies across all dynasties with chronological ordering
- **Structure**: Hierarchical JSON with metadata, dynasty ordering, and frequency matrices

#### 2. **book_variant_matrix_with_authors.csv**
- **Purpose**: Book-level frequency analysis with authorship data
- **Content**: Individual text analysis with author attribution and variant frequencies
- **Granularity**: Individual book/text level
- **Applications**: Author-specific linguistic analysis, text-level frequency patterns

#### 3. **dynasty_variant_summary.csv**
- **Purpose**: Aggregated dynasty-level frequency summaries
- **Content**: Statistical summaries for each dynasty period
- **Metrics**: Total books analyzed, unique authors, variant frequencies, statistical measures

#### 4. **author_variant_analysis.csv**
- **Purpose**: Author-centric analysis of character variant usage
- **Content**: Individual author patterns and preferences in character variant selection
- **Applications**: Stylistic analysis, regional variation studies

## 📈 Visualization Categories

### 1. **Dynasty-Level Analysis**
Each dynasty directory contains:
- `{dynasty}_book_data.csv` - Individual book frequency data
- `{dynasty}_summary.json` - Statistical summary and metadata
- HTML/PNG visualization files for interactive and static viewing

### 2. **Timeline Evolution Analysis**
- **Chronological Progression**: Ordered visualization of character evolution over time
- **Cross-Dynasty Trends**: Identification of long-term linguistic changes
- **Format Options**: Interactive HTML and publication-ready PNG outputs

### 3. **Optimized Visualizations**
Curated subset focusing on:
- **Top 50 books per dynasty** for clarity and performance
- **Minimum frequency threshold ≥ 0.1** for statistical significance
- **Dual format outputs**: Interactive exploration (HTML) and presentation-ready (PNG)
- **Enhanced readability**: Optimized chart layouts and typography

## 🎨 Visualization Features

### Interactive Elements
- **Plotly-based Interactive Charts**: Zoom, pan, and hover functionality
- **Multi-format Support**: HTML for exploration, PNG/SVG for publication
- **Responsive Design**: Optimized for various screen sizes and presentations

### Analysis Types
- **Frequency Bar Charts**: Character variant usage comparison
- **Evolution Timelines**: Temporal frequency progression
- **Heatmaps**: Dynasty-book frequency matrices
- **Ranking Visualizations**: Top books/authors by variant usage
- **Comparative Dashboards**: Cross-dynasty statistical comparison

## 🔬 Research Applications

### Historical Linguistics
- **Diachronic Analysis**: Track character evolution across historical periods
- **Period-Specific Patterns**: Identify dynasty-specific linguistic preferences
- **Quantitative Validation**: Statistical verification of linguistic hypotheses

### Comparative Studies
- **Inter-Dynasty Comparison**: Cross-period linguistic variation analysis
- **Author-Specific Studies**: Individual writing style and preference analysis
- **Regional Variations**: Geographic and temporal linguistic differences

### Digital Humanities
- **Large-Scale Corpus Analysis**: Computational processing of historical texts
- **Visualization-Driven Discovery**: Pattern identification through data visualization
- **Reproducible Research**: Documented methodology and replicable analysis

## 📊 Key Findings & Insights

### Dynasty-Specific Patterns
- **14 Dynasty Periods Analyzed**: From 元魏 through 清代
- **2000+ Books Processed**: Comprehensive coverage of historical Chinese literature
- **300+ Authors Identified**: Individual authorship attribution and analysis

### Statistical Overview
- **Frequency Thresholds**: Variants with ≥0.1 frequency for meaningful analysis
- **Book-Level Granularity**: Individual text analysis rather than corpus-level aggregation
- **Temporal Ordering**: Chronologically arranged for evolution tracking

## 🛠️ Technical Specifications

### Data Formats
- **JSON**: Structured metadata and frequency evolution data
- **CSV**: Tabular data for statistical analysis and spreadsheet integration
- **HTML**: Interactive visualizations with Plotly.js
- **PNG**: High-resolution static visualizations for publication

### Processing Pipeline
1. **Historical Text Corpus Processing**
2. **Character Variant Identification and Classification**
3. **Book-Level Frequency Analysis with Metadata Extraction**
4. **Dynasty-Level Aggregation and Statistical Analysis**
5. **Timeline Evolution Tracking and Visualization Generation**
6. **Optimization and Curation for Enhanced Readability**

### Optimization Features
- **Performance Enhancement**: Filtered datasets for faster loading and interaction
- **Visual Clarity**: Optimized chart layouts and reduced data noise
- **Multi-Format Output**: Both exploratory and presentation-ready visualizations

## 📚 Usage Guidelines

### For Researchers
1. **Start with `optimized_top_n_books_dynasty_level_analysis/`** for an overview
2. **Use `dynasty_summary_dashboard.html`** for cross-dynasty comparison
3. **Drill down to specific dynasties** for detailed analysis
4. **Reference `dynasty_level_analysis_complete_dataset/`** for raw data access

### For Students
- Interactive HTML files provide engaging exploration of historical patterns
- PNG files suitable for presentations and reports
- README files in each directory explain specific analysis focuses

### For Technical Users
- Raw CSV/JSON data available for custom analysis
- Reproducible visualization pipeline
- Documented data structures and processing methodology

## 🎯 Research Context

This visualization project supports research in:
- **Historical Chinese Linguistics**: Quantitative analysis of character evolution
- **Digital Humanities**: Computational approaches to literary and linguistic studies
- **Corpus Linguistics**: Large-scale pattern analysis in historical texts
- **CHIN4101 Coursework**: Academic analysis of Chinese language development

## 📄 Data Sources & Methodology

### Corpus Foundation
- **Traditional Chinese Classical Literature**: Multi-dynasty text collection
- **Mandoku Format Processing**: Standardized historical text formatting
- **Author Attribution**: Systematic extraction of authorship metadata
- **Chronological Ordering**: Historical period-based temporal organization

### Analysis Methodology
- **Character Variant Classification**: Systematic identification of 們 and related variants
- **Frequency Calculation**: Book-level and dynasty-level statistical analysis
- **Temporal Evolution Tracking**: Chronological progression analysis
- **Statistical Validation**: Significance testing and confidence scoring

## 📄 License

Open source - suitable for academic research and educational purposes.

## 📚 Citation

If you use this dataset or tool in your research, please cite the project or contact the author for more information.

**Contributed by:**
- **Ye Tsz Yu Candy**
- Bachelor of Arts
- Majors in Chinese Language and Literature, and Computer Science
- The University of Hong Kong
- Email: u3607570@connect.hku.hk

---

**Academic Context**: CHIN4101 Topical research in Chinese language and literature

**Research Focus**: Computational analysis of character variant evolution across Chinese dynasties

**Methodology**: Quantitative corpus linguistics with comprehensive visualization

**Generated from**: Historical Chinese Word Analysis Tool (Self-written code)

**Analysis Date**: October 2025

**Dataset Coverage**: 85000+ Books

For questions about methodology or data access, please refer to the source analysis tool documentation or contact the research team.