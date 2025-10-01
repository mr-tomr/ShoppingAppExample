# Grocery Store Aisle Map & Shopping List Reorder Instructions (with Side of Aisle, Updated Pasta Placement)

This file gives ChatGPT both the **store map** and the **rules** it should always follow when reordering a shopping list.  

When a user pastes in a shopping list:  
- **Reorder the items** by walking order (Aisle 1 west → Aisle 15 east, plus walls & departments).  
- **Indicate side of aisle** (west/east) for each item, using the aisle sign photos.  

---

## Side-of-Aisle Rules

- **Aisle 1**: photo taken from **north end**  
  - Left of sign → **East side**  
  - Right of sign → **West side**  
- **All other aisles (2–15)**: photos taken from **south end**  
  - Left of sign → **West side**  
  - Right of sign → **East side**  

---

## Aisle Map (with Side)

**Aisle 1** (north photo)  
- **East side**: Dairy, Milk, Yogurt, Pudding, Cheese  
- **West side**: Lunch meat, Breakfast meats, Juice/Punch  

**Aisle 2** (south photo)  
- **West side**: Bottled juice, Kool-Aid, Tortillas  
- **East side**: Salad dressing, Vinegar, Ketchup/Mustard  

**Aisle 3** (south photo) — *updated placement*  
- **West side**: Soup, Rice  
- **East side**: Pasta, Canned meat, Hispanic foods  

**Aisle 4** (south photo)  
- **West side**: Oil/Shortening, Flour/Sugar  
- **East side**: Gelatin, Cake mixes, Baking needs  

**Aisle 5** (south photo)  
- **West side**: Canned fruit, Canned vegetables, Canned beans  
- **East side**: Frozen entrées, Frozen vegetables, Frozen pizza  

**Aisle 6** (south photo)  
- **West side**: Frozen breakfast, Frozen desserts, Ice cream  
- **East side**: Crackers, Cookies  

**Aisle 7** (south photo)  
- **West side**: Salty snacks, Chips  
- **East side**: Popcorn, Pretzels  

**Aisle 8** (south photo)  
- **West side**: Specialty mixers, Coffee  
- **East side**: Soda  

**Aisle 9** (south photo)  
- **West side**: Boxed cereal, Bag cereal, Pancake/Syrup  
- **East side**: Nutrition/Diabetic, Hot cereal, Instant breakfast, Protein drinks/shakes/powders  

**Aisle 10** (south photo)  
- **West side**: Paper towels, Bath tissue, Facial tissue  
- **East side**: Foil/Bags/Wrap, Picnic, Charcoal  

**Aisle 11** (south photo)  
- **West side**: Dog snacks, Dry dog food, Canned dog food  
- **East side**: Pet supplies, Cat food, Cat litter  

**Aisle 12** (south photo)  
- **West side**: Household cleaners, Waxes/Polish, Air fresheners  
- **East side**: Liquid dish soap, Laundry detergent, Bleach/Fabric care  

**Aisle 13** (south photo)  
- **West side**: Bottled water, Candy  
- **East side**: Sports drinks, Snacks  

**Aisle 14** (south photo)  
- **West side**: Bread  
- **East side**: Peanut butter/Jelly  

**Aisle 15** (south photo)  
- **West side**: Bakery  
- **East side**: Deli, Specialty Cheeses  

---

## Instructions to ChatGPT

When given a shopping list:  

1. **Match** each item to its aisle/department and side.  
2. **Reorder** by walking order: Fresh Vegetables → Fresh Fruit → Packaged Fruit → Meat → Frozen (east of Meat) → Aisles 1–15 → Pharmacy → Deli & Bakery.  
3. **Show each aisle heading** with items underneath.  
4. For aisle items, **append (west side) or (east side)**.  
5. **If item cannot be mapped**, place it under **Unmapped Items**.  

---

## Example Usage

**Input Shopping List**  
