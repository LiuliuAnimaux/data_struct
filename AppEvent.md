#AppEvent
{

*'type'* : \<Number>,

*'json'* : \<Dictionary>,

}

#Example

###1. Web
	{
		'type' : 1,
		'json' : {
			'web_title' : <String>,
			'web_url' : <String>,
		},
	}

###2. Pet

	{
		'type' : 2,
		'json' : {
			'pet_id' : <String>,
		},
	}


###3. Photo

	{
		'type' : ,
		'json' : {
			'photo_id' : <String>,
		},
	}


###4. User

	{
		'type' : ,
		'json' : {
			'user_id' : <String>,
		},
	}


###5. Chat

	{
		'type' : ,
		'json' : {
			'user_id' : <String>,
			'user_pic' : <String>,
			'user_name' : <String>,
		},
	}


###6. Comment

	{
		'type' : ,
		'json' : Null,
	}


###7. Praise

	{
		'type' : ,
		'json' : Null,
	}


###8. Fans

	{
		'type' : ,
		'json' : Null,
	}


###9. Taobao item

	{
		'type' : ,
		'json' : {
			'open_id' : <String>,
			'item_type' : <String>,
		},
	}


###10. Post

	{
		'type' : ,
		'json' : {
			'post_id' : <String>,
			'post_type' : <String>,
		},
	}


###11. Taobao url

	{
		'type' : ,
		'json' : {
			'taobao_url ' : <String>,
		},
	}


###12. Taobao order

	{
		'type' : ,
		'json' : {
			'order_items' : [
				{
					'itemId' : <String>,
					'skuId' : <String>,
					'quantity' : <String>,
				},
			],
		},
	}


###13. Share link to weixin

	{
		'type' : ,
		'json' : {
			'scene' : <String>,
			'thumbUrl' : <String>,
			'title' : <String>,
			'description' : <String>,
			'link' : <String>,
		},
	}


###14. Share weibo with an id

	{
		'type' : ,
		'json' : {
			'weibo_id' : <String>,
		},
	}


###15. Adopting

	{
		'type' : ,
		'json' : {
			'pet' : <Pet>,
		},
	}


###16. Mating

	{
		'type' : ,
		'json' : {
			'pet' : <Pet>,
		},
	}


###17. Copy

	{
		'type' : ,
		'json' : {
			'copy_text' : <String>,
		},
	}


###18. Show share panel

	{
		'type' : ,
		'json' : {
			'weibo_id' : <String>,
			'link' : <String>,
			'title' : <String>,
			'description' : <String>,
			'thumbUrl' : <String>,
		},
	}