# Noktaları koydum
points = [(1, 2), (3, 4), (5, 6), (7, 8)]

# Öklid mesafesi hesaplamak için bir fonksiyon tanımladım
def euclideanDistance(point1, point2):
    return ((point1[0] - point2[0]) ** 2 + (point1[1] - point2[1]) ** 2) ** 0.5

# her noktalar arasındaki mesafeyi hesapladım.
distances = []
for h in range(len(points)):
    for s in range(i + 1, len(points)):
        distance = euclideanDistance(points[h], points[s])
      
  
# oklid için min mesafeyi buldum
min_distance = min(distances)
print(f"Minimum mesafe: {min_distance:}")
