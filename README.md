# Community Event Planning Projects

This repository contains two community event planning projects implemented using different algorithmic approaches:

## Projects

### 1. Dodol Feast Preparation and Team Rotation Plan
**File:** `Dodol_Feast_Preparation.ipynb`

A constraint satisfaction problem solved using backtracking search to create an optimal team rotation schedule for a 4-day dodol feast.

**Problem:**
- 7 teams need to stir a pot of dodol for 4 consecutive days
- Each team works 4-hour shifts
- Each team must work at least 8 hours total during the feast
- No team should work more than 4 hours per day
- 4 teams work each day (6 shifts per day)

**Solution:**
- Uses backtracking search with constraint satisfaction
- Ensures all teams meet minimum hour requirements
- Balances workload across teams

### 2. Kindergarten Holiday Gift Set Planning
**File:** `Kindergarten_Holiday_Gift_Planning.ipynb`

A genetic algorithm solution for optimizing holiday gift sets within budget constraints.

**Problem:**
- 25 students (15 girls, 10 boys)
- Budget: RM200.00 total
- Each set needs at least 2 stationery items and 1 food item
- Wrapper cost: RM1.00 per set (blue for boys, pink for girls)

**Available Items:**
| Item | Price (RM) | Category |
|------|------------|----------|
| Mini sketch book | 2.00 | Stationery |
| 2B pencil | 1.00 | Stationery |
| Color pencil | 3.00 | Stationery |
| Magic pen | 3.00 | Stationery |
| Potato chip | 2.00 | Food |
| Milo packet | 1.00 | Food |
| Chipsmore Biscuit | 2.00 | Food |
| Milk biscuit | 3.00 | Food |

**Solution:**
- Genetic algorithm with tournament selection
- One-point crossover and mutation operators
- Fitness function considers budget, stationery, and food constraints

## Technologies Used

- **Python 3.8+**
- **Jupyter Notebooks**
- **Genetic Algorithms**
- **Constraint Satisfaction Problems**
- **Backtracking Search**

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/SoObai/Community-Event-Planning-Projects.git
```

2. Navigate to the project directory:
```bash
cd Community-Event-Planning-Projects
```

3. Open the Jupyter notebooks:
```bash
jupyter notebook
```

4. Run the cells in either notebook to see the algorithms in action.

## Project Structure

```
Community-Event-Planning-Projects/
├── README.md
├── Dodol_Feast_Preparation.ipynb
└── Kindergarten_Holiday_Gift_Planning.ipynb
```

## Author

**Obai Ali Abdelrahman**

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to submit issues and enhancement requests!

---

## 📦 1. Bundles of Joy – Kindergarten Holiday Gift Set Planning

**Objective:**  
Plan and organize 25 holiday gift sets for kindergarten students (15 girls and 10 boys) within a fixed budget of RM200.00.

**Key Details:**
- RM1.00 wrapping cost per gift (pink for girls, blue for boys)
- Each gift set must include at least **2 stationery items**
- Final gift composition is planned within the remaining budget (RM175.00 for items)
- Item choices include biscuits, drinks, and various stationery (e.g., pencils, sketchbooks, color sets)

**Focus Areas:**
- Budget allocation per student
- Gender-specific wrapping and item selection
- Educational value and fairness

📁 Related File: `kindergarten_gift_set_plan.md`

---

## 🍯 2. Stirring Traditions – Dodol Feast & Team Rotation Plan

**Objective:**  
Plan a 4-day dodol cooking feast in Village ABC, to be streamed live on Facebook and shared with the community.

**Key Details:**
- 7 teams rotate to stir dodol in a large pot
- Each shift lasts **4 hours**
- Each team stirs for **no more than 4 hours per day**
- Each team must contribute **at least 8 hours in total** over 4 days
- Promotes cultural heritage and teamwork

**Focus Areas:**
- Team scheduling and workload fairness
- Continuous operation planning (24-hour coverage)
- Cultural promotion via live streaming

📁 Related File: `dodol_feast_rotation_plan.md`

---

## 📌 Repository Structure

```bash
├── README.md
├── kindergarten_gift_set_plan.md
├── dodol_feast_rotation_plan.md
└── images/
    └── (optional visuals or planning diagrams)
```

---

## 💡 Author

Obai Ahmed  
📧 obaialid45@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/obai-ahmed-b7697433a/)  
🔗 [GitHub](https://github.com/SoObai)

---

Feel free to fork, adapt, or reference this repository for community or event planning projects.
