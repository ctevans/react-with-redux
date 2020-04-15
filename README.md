# App's State in Store.

This is how your data will look like in the redux store.

{
inventory: [{
			id: 1,
			itemTypeId: 13,
			currentStock: 5,
			name: "TV 1337",

		},
		{
			id: 2,
			itemTypeId: 17,
			currentStock: 0,
			name: "Awesome Cake",

		},
		{
			id: 3,
			itemTypeId: 87,
			currentStock: 99,
			name: "Bad Cake",

		}

	],
	userCart: {
		userId: 1,
		selectedItems: [
			13, 2, 3
		]
	}

}