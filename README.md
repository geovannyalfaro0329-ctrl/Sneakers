# Sneakers
unit 7 
enum SneakerBrand: String {
    case nike = "Nike"
    case adidas = "Adidas"
    case jordan = "Jordan"
    case newBalance = "New Balance"
}

enum SneakerCondition {
    case new
    case excellent
    case good
    case fair
    case poor
}

// MARK: - Part 3: Create the Sneaker Structure
struct Sneaker {
    var modelName: String
    var brand: SneakerBrand
    var size: Double
    var condition: SneakerCondition
    var purchasePrice: Double
    var estimatedValue: Double
}

// MARK: - Part 4: Create Three Sneakers
var sneaker1 = Sneaker(
    modelName: "Air Jordan 1 High OG",
    brand: .jordan,
    size: 10.5,
    condition: .new,
    purchasePrice: 180.0,
    estimatedValue: 320.0
)

var sneaker2 = Sneaker(
    modelName: "Ultraboost Light",
    brand: .adidas,
    size: 11.0,
    condition: .excellent,
    purchasePrice: 190.0,
    estimatedValue: 150.0
)

var sneaker3 = Sneaker(
    modelName: "Air Force 1 '07",
    brand: .nike,
    size: 10.0,
    condition: .good,
    purchasePrice: 115.0,
    estimatedValue: 95.0
)


