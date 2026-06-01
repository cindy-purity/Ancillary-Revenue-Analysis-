# Solstice Opal Hotel - Ancillary Revenue Analysis

A data analysis project exploring which guest segments generate the most ancillary revenue (spa, dining, and activities) at Solstice Opal Hotel, with actionable recommendations for leadership.

---

## Project Overview

Solstice Opal Hotel earns revenue not just from room bookings, but from what guests spend on extras: spa treatments, dining, and activities. This analysis identifies the highest-value guest segments and uncovers patterns in spending behavior across loyalty tiers, booking channels, and travel purpose - giving leadership a clear picture of where to focus their retention and upselling strategies.

**Key metric:** Average Ancillary Revenue per Stay (AARS)

---

## Dataset

Three interconnected datasets were used:

| File | Description | Rows |
|------|-------------|------|
| `da_sample_guest_profiles.csv` | Guest ID, loyalty tier, marketing consent | 400 |
| `da_sample_stay_details.csv` | Check-in date, booking channel, reason for stay, party size | 600 |
| `da_sample_ancillary_spend.csv` | Spend transactions by category (dining, spa, activities) | 800 |

---

## Key Findings

### 1. Platinum guests are the highest-value segment by a wide margin
Platinum loyalty members averaged **$351.86 per stay** in ancillary spend - more than double the hotel average of $178.46, and nearly 2.5x that of Non-members ($141.39). They represent only 9% of guests but contribute disproportionately to total revenue.

### 2. Leisure guests outspend business guests overall
Leisure guests averaged **$187.15 per stay** vs $169.42 for business guests. However, the pattern flips for Silver-tier guests, where business travelers actually spend more - suggesting targeted upsell opportunities within that segment.

### 3. Direct website bookings drive the highest ancillary spend
Guests who booked via the hotel website averaged **$191.64 per stay**, compared to $171.58 via travel agents and $161.33 via corporate channels - indicating that direct-channel guests may have stronger brand affinity and higher engagement.

### 4. Dining is the dominant revenue category
Of the three ancillary categories, dining generated the most revenue at **$32,110.86**, followed by spa ($19,272.06) and activities ($9,236.97).

### 5. Nearly 12% of stays produced zero ancillary spend
68 out of 571 stays (11.9%) had no ancillary transactions at all - representing an untapped revenue opportunity, particularly among Non-member guests.

---

## Recommendations

**1. Prioritize Platinum retention.**
Platinum guests generate nearly $352 per stay on average. A dedicated retention strategy (early check-in, personalized offers, complimentary upgrades) could significantly protect this revenue stream.

**2. Target leisure Non-members with dining promotions.**
Non-members on leisure stays are the largest group with the most room to grow. Bundled dining offers or welcome packages at check-in could convert zero-spend guests into active spenders.

**3. Incentivize direct bookings.**
Website-channel guests spend the most. Marketing campaigns that drive direct bookings over travel agent channels could boost ancillary revenue per stay across the board.

---

## Tools Used

- Python 3
- pandas
- NumPy
- Matplotlib

---

## How to Run

Open `notebook.ipynb` in Jupyter Notebook, DataLab, VS Code, or GitHub's notebook viewer. Keep all CSV files in the same folder as the notebook.

To install dependencies:

```bash
pip install -r requirements.txt
```

---

## Project Structure

```
├── notebook.ipynb                    # Full analysis notebook
├── chart.png                         # Ancillary revenue by guest segment
├── da_sample_guest_profiles.csv      # Guest profile data
├── da_sample_stay_details.csv        # Stay records
├── da_sample_ancillary_spend.csv     # Spend transactions
├── requirements.txt                  # Python dependencies
└── README.md                         # Project documentation
```

---

*Analysis conducted using Python and pandas. Dataset provided by DataCamp.*
