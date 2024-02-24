@startuml
left to right direction
actor "Квартиросъемщик" as Renter
actor "Владелец жилья" as Owner
actor "Агент жилищного \nагентства" as Agent

rectangle "Информационная\nсистема жилищного\nагентства" {
    Renter -- (Поиск жилья)
    Renter -- (Подбор вариантов)
    Renter -- (Оформление аренды)

    Owner -- (Размещение объявлений)
    Owner -- (Просмотр заявок)
    Owner -- (Оформление аренды)

    Agent -- (Управление базой данных)
    Agent -- (Помощь пользователям)
    Agent -- (Согласование условий)
}
@enduml
