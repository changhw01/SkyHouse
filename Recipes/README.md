CodeForTomorrow 開放食庫測試用食譜資料 (Josn-LD 格式)

http://food.codefortomorrow.org/

  "@context":
  {
    "url": "http://schema.org/url",
    "name": "http://schema.org/name",
    "cuisine": "http://schema.org/recipeCuisine",
    "ingredients":
    {
      "@id": "http://schema.org/ingredients",
      "@container": "@set"
    },
    "seasonings": 
    {
      "@id": "http://food-linked-data.org/seasonings",
      "@container": "@set"
    },
    "instructions":
    {
      "@id": "http://schema.org/recipeInstructions",
      "@container": "@list"
    }
  }
