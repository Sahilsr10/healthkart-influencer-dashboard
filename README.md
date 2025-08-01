# healthkart-influencer-dashboard
This project is an open-source dashboard built to help HealthKart track, visualize, and analyze the return on investment (ROI) of their influencer marketing campaigns.


# Influencer Marketing ROI Dashboard

🚀 Live Demo
You can view and interact with the live dashboard here:
https://p7mwzh-3000.csb.app/

A comprehensive open-source dashboard for tracking, visualizing, and analyzing the return on investment (ROI) of influencer marketing campaigns. Built specifically for HealthKart to empower data-driven marketing decisions and optimize influencer partnerships.

<img width="1656" height="901" alt="Screenshot 2025-07-22 at 7 10 56 PM" src="https://github.com/user-attachments/assets/8dd24967-91bc-4c5c-8ee8-564300d0b5c9" />

<img width="1653" height="577" alt="Screenshot 2025-07-22 at 7 11 10 PM" src="https://github.com/user-attachments/assets/71ba992f-9b24-424f-8ec2-fc465d1361f1" />


## 🚀 Features

- **📊 Comprehensive Analytics**: Single-pane dashboard with key metrics including total revenue, spend, incremental ROAS, and order tracking
- **📈 Performance Visualization**: Track campaign revenue vs. payout over time with brand contribution analysis
- **🔬 Advanced Filtering**: Dynamic filtering by brand, platform (Instagram, YouTube), and influencer category (Fitness, Beauty)
- **💡 Influencer Insights**: 
  - Top performers ranking by ROAS
  - Poor ROI identification for strategic optimization
  - Sortable performance tables
- **📄 Export Functionality**: CSV export for filtered top-performing influencers
- **💾 Data Simulation**: Pre-loaded with mock campaign data for immediate testing

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Charts**: Recharts
- **Styling**: Tailwind CSS
- **Icons**: Lucide React

## 🏃‍♂️ Quick Start

### Prerequisites
- Modern browser with JavaScript enabled
- React development environment

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/influencer-marketing-roi-dashboard.git
cd influencer-marketing-roi-dashboard
```


## 📊 Data Structure

The dashboard operates on four core datasets:

| Dataset | Purpose | Key Fields |
|---------|---------|------------|
| `influencers` | Influencer directory | id, name, category, platform, follower_count |
| `posts` | Content tracking | influencer_id, platform, reach, engagement |
| `tracking_data` | Performance metrics | campaign, orders, revenue, brand |
| `payouts` | Investment tracking | influencer_id, rate, total_payout |

### Key Assumptions
- **Incremental ROAS**: Calculated as `Total Revenue / Total Payout`
- **Attribution**: All tracked revenue assumed incremental
- **Payout Attribution**: Post-based payouts assigned to first post date for visualization

## 🎯 Use Cases

- **Marketing Teams**: Optimize influencer strategy and budget allocation
- **Performance Analysis**: Identify top-performing partnerships and underperforming campaigns
- **ROI Tracking**: Monitor incremental return on ad spend across brands and platforms
- **Strategic Planning**: Data-driven decisions for future influencer partnerships

## 🔧 Customization

The dashboard supports easy customization for different brands and metrics:

- Modify brand categories in the filtering system
- Add new performance metrics
- Customize ROAS calculation methodology
- Extend export functionality

## 📈 Future Enhancements

- Real-time data integration via APIs
- Advanced engagement rate analysis
- Baseline incrementality modeling
- Automated reporting features
- Multi-brand comparison tools

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.



## 🏢 About

Built for HealthKart's marketing optimization needs. This tool helps track performance across MuscleBlaze, HKVitals, and Gritzo brand campaigns.

---

**Note**: This dashboard includes simulated data for demonstration purposes. For production use, integrate with your actual campaign tracking systems.
