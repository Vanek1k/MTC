class CityCoverage:
    def __init__(self, city, price_tower_5g, price_tower_4g, price_equipment, price_install, profit_people, radius_5G, radius_4G):
        self.city = city
        self.price_tower_5g = price_tower_5g
        self.price_tower_4g = price_tower_4g
        self.price_equipment = price_equipment
        self.price_install = price_install
        self.profit_people = profit_people
        self.radius_5G = radius_5G
        self.radius_4G = radius_4G

    def calculate_towers(self, radius):
        # рассчитываем количество вышек, необходимых для покрытия заданного радиуса
        towers = radius // 1000

        if radius % 1000 != 0:
            towers += 1

        return towers

    def calculate_total_cost(self):
        # рассчитываем количество вышек для 5G
        towers_5g = self.calculate_towers(self.radius_5G)

        # рассчитываем количество вышек для 4G
        towers_4g = self.calculate_towers(self.radius_4G)

        # рассчитываем стоимость оборудования
        equipment_cost = (self.price_tower_5g * towers_5g) + (self.price_tower_4g * towers_4g) + self.price_equipment

        # рассчитываем стоимость установки
        install_cost = (self.price_install * towers_5g) + (self.price_install * towers_4g)

        # рассчитываем общую стоимость
        total_cost = equipment_cost + install_cost

        return total_cost

    def calculate_profit(self, radius, profit_per_user, technology, months):
        # рассчитываем количество вышек для заданного радиуса
        towers = self.calculate_towers(radius)

        # рассчитываем общий доход от вышки за заданный период
        if technology == "5G":
            profit = profit_per_user * towers * self.profit_people * months * 30
        elif technology == "4G":
            profit = profit_per_user * towers * self.profit_people * months * 15

        return profit

# пример использования класса для рассчета стоимости покрытия города и дохода от каждой вышки
city = input("Введите название города: ")
price_tower_5g = int(input("Введите стоимость вышки 5G: "))
price_tower_4g = int(input("Введите стоимость вышки 4G: "))
price_equipment = int(input("Введите стоимость оборудования: "))
price_install = int(input("Введите стоимость установки вышки: "))
profit_people = int(input("Введите доход от пользователя: "))
radius_5G = float(input("Введите радиус зоны покрытия 5G: "))
radius_4G = float(input("Введите радиус зоны покрытия 4G: "))
months = int(input("Введите количество месяцев для расчета дохода: "))

city_coverage = CityCoverage(city, price_tower_5g, price_tower_4g, price_equipment, price_install, profit_people, radius_5G, radius_4G)
total_cost = city_coverage.calculate_total_cost()
print("Стоимость покрытия города", city, "составляет", total_cost, "рублей.")

profit_5g = city_coverage.calculate_profit(radius_5G, profit_per_user=10, technology="5G", months=months)
print("Доход от каждой вышки 5G за", months, "месяцев составляет", profit_5g, "рублей.")

profit_4g = city_coverage.calculate_profit(radius_4G, profit_per_user=5, technology="4G", months=months)
print("Доход от каждой вышки 4G за", months, "месяцев составляет", profit_4g, "рублей.")

if profit_5g > profit_4g:
    print("Вышка 5G прибыльнее")
else:
    print("Вышка 4G прибыльнее")
