# tiktok-symphony

## login
'''
https://ads.tiktok.com/business-chatbot/login?biz_type=1


{
    "code": 0,
    "msg": "",
    "data": {
        "app_id": 4684,
        "user_id": "7402689290701194256",
        "user_type": 1,
        "biz_type": 1,
        "account_id": "",
        "extra": {
            "industry": "Bags",
            "product": "health products",
            "selling_point": "natural, effective, high-quality",
            "target_audience": "people who care about their health"
        }
    }
}
'''


## init
'''
https://ads.tiktok.com/business-chatbot/conversation/init?platform_account=7402689290701194256&biz_type=1


{
    "code": 0,
    "msg": "",
    "data": {
        "last_conversation": {
            "conversation_id": "7404203279917400065",
            "biz_type": 1,
            "user_id": 7402689290701194256,
            "account_id": "",
            "biz_extra": "",
            "status": 0,
            "created_time": "2024-08-17T20:12:04.807Z",
            "updated_time": "2024-08-17T20:12:12.029Z",
            "messages": [
                {
                    "message_id": "66c10415405d04a6e6620168",
                    "conversation_id": "7404203279917400065",
                    "role": "user",
                    "contents": [
                        {
                            "type": "token",
                            "data": {
                                "content": "herb",
                                "token_num": 2
                            }
                        },
                        {
                            "type": "ab_test",
                            "data": {
                                "parameters": "{\"satisfaction\":false,\"t2i\":false,\"factory\":false,\"prompt_extend\":false,\"permanent_prompt\":false}"
                            }
                        }
                    ],
                    "log_id": "202408172012049A6104E5B17FFA435FFD",
                    "user_option": {},
                    "user_context": {},
                    "created_time": "2024-08-17T20:12:05.72Z",
                    "update_time": "0001-01-01T00:00:00Z"
                },
                {
                    "message_id": "66c10415405d04a6e6620169",
                    "conversation_id": "7404203279917400065",
                    "role": "assistant",
                    "contents": [
                        {
                            "type": "extra",
                            "data": {
                                "ab_params": "{\"dynamic_hint\": {\"group\": \"online\"}, \"satisfaction\": false, \"t2i\": false, \"factory\": false, \"prompt_extend\": false, \"permanent_prompt\": false, \"response_language\": \"English\"}",
                                "backend_detect_language": "English",
                                "hint_language": "English",
                                "question": "",
                                "question_input": "{}",
                                "response_language": "English",
                                "use_case": "Reject"
                            }
                        },
                        {
                            "type": "hints",
                            "data": {
                                "Hints": [
                                    {
                                        "short_text": "Find some keywords driving ad performance.",
                                        "complete_text": "Find some keywords driving ad performance.",
                                        "params": null,
                                        "hint_type": 1
                                    },
                                    {
                                        "short_text": "Show me some TikTok ad examples.",
                                        "complete_text": "Show me some TikTok ad examples.",
                                        "params": null,
                                        "hint_type": 1
                                    },
                                    {
                                        "short_text": "Find me some top products on TikTok.",
                                        "complete_text": "Find me some top products on TikTok.",
                                        "params": null,
                                        "hint_type": 1
                                    },
                                    {
                                        "short_text": "Write a TikTok ad script for me.",
                                        "complete_text": "Write a TikTok ad script for me.",
                                        "params": null,
                                        "hint_type": 1
                                    }
                                ]
                            }
                        },
                        {
                            "type": "token",
                            "data": {
                                "pre_content": "I\u003c|endoftext|\u003e",
                                "content": "I appreciate your understanding that your recent request may not align perfectly with the creative scope of TikTok, or it could potentially conflict with our platform's guidelines. As such, I might not be able to provide a comprehensive response. However, I'm more than willing to assist with any other questions or ideas you might have that are related to TikTok's creative and advertising realm!\u003c|endoftext|\u003e",
                                "gpt_id": "cmpl-bebedd6c95ce4828a44e76f33f865c46",
                                "token_num": 81
                            }
                        }
                    ],
                    "log_id": "202408172012049A6104E5B17FFA435FFD",
                    "user_option": {},
                    "user_context": {},
                    "created_time": "2024-08-17T20:12:12.026Z",
                    "update_time": "0001-01-01T00:00:00Z",
                    "pre_message_id": "66c10415405d04a6e6620168"
                }
            ],
            "total_cnt": 2
        },
        "conversation_list": [
            {
                "conversation_id": "7402689529552928769",
                "biz_type": 1,
                "user_id": 7402689290701194256,
                "account_id": "",
                "biz_extra": "",
                "status": 0,
                "created_time": "2024-08-13T18:17:20.024Z",
                "updated_time": "2024-08-14T01:41:43.1Z",
                "messages": [
                    {
                        "message_id": "66bc0b4b405d04a6e60d3ba0",
                        "conversation_id": "7402689529552928769",
                        "role": "user",
                        "contents": [
                            {
                                "type": "token",
                                "data": {
                                    "content": "Please recommend some popular products in the health.",
                                    "token_num": 9
                                }
                            },
                            {
                                "type": "ab_test",
                                "data": {
                                    "parameters": "{\"satisfaction\":false,\"t2i\":false,\"factory\":false,\"prompt_extend\":false,\"permanent_prompt\":false}"
                                }
                            }
                        ],
                        "log_id": "20240814014129D917A466940F706A11E5",
                        "user_option": {},
                        "user_context": {},
                        "created_time": "2024-08-14T01:41:31.158Z",
                        "update_time": "0001-01-01T00:00:00Z"
                    },
                    {
                        "message_id": "66bc0b4b405d04a6e60d3ba1",
                        "conversation_id": "7402689529552928769",
                        "role": "assistant",
                        "contents": [
                            {
                                "type": "extra",
                                "data": {
                                    "ab_params": "{\"dynamic_hint\": {\"group\": \"online\"}, \"satisfaction\": false, \"t2i\": false, \"factory\": false, \"prompt_extend\": false, \"permanent_prompt\": false, \"response_language\": \"English\"}",
                                    "backend_detect_language": "English",
                                    "hint_language": "English",
                                    "question": "Recommend products",
                                    "question_input": "{\"industry_list\": [29000000000], \"data_source\": null, \"country_codes\": [], \"num_of_result\": 5, \"period\": null, \"user_input\": \"Please recommend some popular products in the health.\"}",
                                    "response_language": "English",
                                    "use_case": "Find Inspiration"
                                }
                            },
                            {
                                "type": "hints",
                                "data": {
                                    "Hints": [
                                        {
                                            "short_text": "Tell me more.",
                                            "complete_text": "Tell me more.",
                                            "params": null,
                                            "hint_type": 1
                                        },
                                        {
                                            "short_text": "Show me some TikTok ad examples.",
                                            "complete_text": "Show me some TikTok ad examples.",
                                            "params": null,
                                            "hint_type": 1
                                        },
                                        {
                                            "short_text": "Show me what's trending on TikTok",
                                            "complete_text": "Show me what's trending on TikTok",
                                            "params": null,
                                            "hint_type": 1
                                        },
                                        {
                                            "short_text": "Write some attention-grabbers for my ad.",
                                            "complete_text": "Write some attention-grabbers for my ad.",
                                            "params": null,
                                            "hint_type": 1
                                        }
                                    ]
                                }
                            },
                            {
                                "type": "elements",
                                "data": {
                                    "style_id": 1,
                                    "elements": {
                                        "url": [
                                            "{\"url\": \"https://ads.tiktok.com/business/creativecenter/product-category/Beauty%20Supplements-700648?index=0\u0026level=l3\", \"name\": \"Top Products - Beauty Supplements\"}",
                                            "{\"url\": \"https://ads.tiktok.com/business/creativecenter/product-category/Wellness%20Supplements-700650?index=0\u0026level=l3\", \"name\": \"Top Products - Wellness Supplements\"}",
                                            "{\"url\": \"https://ads.tiktok.com/business/creativecenter/product-category/Serums%20%26%20Essences-601619?index=0\u0026level=l3\", \"name\": \"Top Products - Serums \u0026 Essences\"}",
                                            "{\"url\": \"https://ads.tiktok.com/business/creativecenter/product-category/Toothbrushes-601697?index=0\u0026level=l3\", \"name\": \"Top Products - Toothbrushes\"}",
                                            "{\"url\": \"https://ads.tiktok.com/business/creativecenter/product-category/Coffee-700612?index=0\u0026level=l3\", \"name\": \"Top Products - Coffee\"}"
                                        ]
                                    }
                                }
                            },
                            {
                                "type": "token",
                                "data": {
                                    "pre_content": "1\u003c|endoftext|\u003e",
                                    "content": "1. Beauty Supplements \u003cstart_url\u003e1\u003c/end_url\u003e - Beauty Supplements are products designed to enhance the health of your skin, hair, and nails. They often contain vitamins, minerals, and other essential nutrients that can contribute to radiant skin, luscious locks, and strong nails. They're a popular choice among individuals seeking to improve their overall beauty and wellness.\n\n2. Wellness Supplements \u003cstart_url\u003e2\u003c/end_url\u003e - Wellness Supplements are a popular choice for those who want to enhance their overall health and wellbeing. These products can include vitamins, minerals, and other nutrients that are essential for maintaining a healthy body and mind. They're a great choice for individuals who want to support their body's natural health processes.\n\n3. Serums \u0026 Essences \u003cstart_url\u003e3\u003c/end_url\u003e - Serums and essences are skincare products that are often packed with powerful active ingredients. Serums are designed to treat specific skin concerns, like wrinkles, dark spots, or dryness, while essences are used to add moisture and balance the skin's pH. They're a popular choice among individuals who take skincare seriously.\n\n4. Toothbrushes \u003cstart_url\u003e4\u003c/end_url\u003e - Toothbrushes are a staple in oral health routines. They're used to remove plaque, prevent cavities, and maintain fresh breath. With various styles and features available, toothbrushes cater to different preferences and needs, making them a popular choice for individuals who prioritize oral hygiene.\n\n5. Coffee \u003cstart_url\u003e5\u003c/end_url\u003e - Coffee is a popular beverage that many people incorporate into their daily routine. It's known for its stimulating effects and rich flavor. Whether it's enjoyed as a morning pick-me-up, an afternoon energy boost, or part of a cozy evening routine, coffee is a favorite for many. It's also often used as an ingredient in various recipes, adding depth to dishes and drinks.\n\nThese are just a few examples of popular health-related products that could be marketed on TikTok. Each of these categories offers a wealth of opportunities for creative and engaging content.\u003c|endoftext|\u003e",
                                    "gpt_id": "cmpl-fa16fcc646b94e3691ebb52a8cbfa3d5",
                                    "token_num": 427
                                }
                            }
                        ],
                        "log_id": "20240814014129D917A466940F706A11E5",
                        "user_option": {},
                        "user_context": {},
                        "created_time": "2024-08-14T01:41:43.096Z",
                        "update_time": "0001-01-01T00:00:00Z",
                        "pre_message_id": "66bc0b4b405d04a6e60d3ba0"
                    }
                ]
            }
        ]
    }
}
'''

## message

'''
https://ads.tiktok.com/business-chatbot/message/?platform_account=7402689290701194256&biz_type=1


platform_account: 7402689290701194256
biz_type: 1

{"conversation_id":"7404203279917400065","page_info":"{\"url_path\":\"/business/creativecenter/inspiration/popular/hashtag\",\"data\":\"{\\\"hashtagIds\\\":[\\\"17007840\\\",\\\"34444604\\\",\\\"7211839\\\",\\\"20921032\\\",\\\"1674856478603269\\\",\\\"1690077568182278\\\",\\\"536098\\\",\\\"7299748756554153989\\\",\\\"20668932\\\",\\\"1656441067076613\\\",\\\"76315\\\",\\\"17438\\\",\\\"809423\\\",\\\"157866\\\",\\\"7065837423057436719\\\",\\\"29589813\\\",\\\"1663240967065606\\\",\\\"1696397650539525\\\",\\\"16228\\\",\\\"68275651\\\"]}\",\"params\":\"{\\\"countryCode\\\":\\\"US\\\",\\\"industryId\\\":\\\"\\\",\\\"query\\\":\\\"\\\",\\\"period\\\":7}\",\"html_text\":\"Browse what's trending now in\\nUnited States\\nFind what performs well on TikTok and better engage with your audience.\\nHashtags\\nDiscover new trends on TikTok through hashtags\\nSongs\\nCreators\\nTikTok Videos\\nIndustry\\nLast 7 days\\nNew to top 100\\nRank\\nHashtags\\nPosts\\nTrend\\nCreators\\nActions\\n1\\n# demure\\nApparel & Accessories\\n77K\\nPosts\\nNo related creator\\nSee analytics\\n2\\n# itendswithus\\nNews & Entertainment\\n79K\\nPosts\\nSee analytics\\n3\\n# blakelively\\nNews & Entertainment\\n60K\\nPosts\\nSee analytics\\n4\\n6\\n# justinbaldoni\\nNews & Entertainment\\n45K\\nPosts\\nNo related creator\\nSee analytics\\n5\\n# bamarush\\nApparel & Accessories\\n52K\\nPosts\\nNo related creator\\nSee analytics\\n6\\n2\\n# itendswithusmovie\\nNews & Entertainment\\n50K\\nPosts\\nNo related creator\\nSee analytics\\n7\\n# billcipher\\nGames\\n68K\\nPosts\\nSee analytics\\n8\\n# novelshort\\nGames\\n78K\\nPosts\\nNo related creator\\nSee analytics\\n9\\n2\\n# colleenhoover\\nEducation\\n49K\\nPosts\\nSee analytics\\n10\\n1\\n# rushtok\\nApparel & Accessories\\n39K\\nPosts\\nNo related creator\\nSee analytics\\n11\\n# breakdancing\\n57K\\nPosts\\nNo related creator\\nSee analytics\\n12\\n# breakdance\\n57K\\nPosts\\nNo related creator\\nSee analytics\\n13\\n6\\n# mindful\\n36K\\nPosts\\nNo related creator\\nSee analytics\\n14\\n# d23\\nNews & Entertainment\\n59K\\nPosts\\nSee analytics\\n15\\n# bookofbill\\nGames\\n56K\\nPosts\\nSee analytics\\n16\\n# lilybloom\\nNews & Entertainment\\n44K\\nPosts\\nSee analytics\\n17\\n# verydemure\\nApparel & Accessories\\n10K\\nPosts\\nNo related creator\\nSee analytics\\n18\\n# itendswithusbook\\nNews & Entertainment\\n43K\\nPosts\\nNo related creator\\nSee analytics\\n19\\n1\\n# rush\\nGames\\n33K\\nPosts\\nNo related creator\\nSee analytics\\n20\\n# meperdientusojos\\n62K\\nPosts\\nNo related creator\\nSee analytics\\nFor data safety reasons, the list shows at most the top 100 most popular content under the corresponding filter criteria.\"}","user_context":{},"user_option":{},"ab_test_param":{"parameters":"{\"satisfaction\":false,\"t2i\":false,\"factory\":false,\"prompt_extend\":false,\"permanent_prompt\":false}"},"message":{"role":"user","content":{"type":"token","data":"herb"}},"target_language":"en"}

"""


```json
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"extra","data":{"ab_params":"{\"dynamic_hint\": {\"group\": \"online\"}, \"satisfaction\": false, \"t2i\": false, \"factory\": false, \"prompt_extend\": false, \"permanent_prompt\": false, \"response_language\": \"English\"}","backend_detect_language":"English","hint_language":"English","question":"","question_input":"{}","response_language":"English","use_case":"Reject"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"hints","data":{"Hints":[{"short_text":"Find some keywords driving ad performance.","complete_text":"Find some keywords driving ad performance.","params":null,"hint_type":1},{"short_text":"Show me some TikTok ad examples.","complete_text":"Show me some TikTok ad examples.","params":null,"hint_type":1},{"short_text":"Find me some top products on TikTok.","complete_text":"Find me some top products on TikTok.","params":null,"hint_type":1},{"short_text":"Write a TikTok ad script for me.","complete_text":"Write a TikTok ad script for me.","params":null,"hint_type":1}]}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"I"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" appreciate"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" your"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" understanding"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" that"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" your"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" recent"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" request"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" may"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" not"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" align"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" perfectly"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" with"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" the"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" creative"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" scope"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" of"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" T"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"ik"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"Tok"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":","}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" or"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" it"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" could"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" potentially"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" conflict"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" with"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" our"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" platform"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"'"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"s"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" guidelines"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"."}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" As"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" such"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":","}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" I"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" might"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" not"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" be"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" able"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" to"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" provide"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" a"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" comprehensive"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" response"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"."}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" However"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":","}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" I"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"'"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"m"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" more"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" than"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" willing"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" to"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" assist"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" with"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" any"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" other"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" questions"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" or"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" ideas"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" you"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" might"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" have"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" that"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" are"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" related"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" to"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" T"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"ik"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"Tok"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"'"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"s"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" creative"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" and"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" advertising"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":" realm"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"!"}},"user_context":{},"user_option":{}}
{"conversation_id":"7404203279917400065","message_id":"66c10415405d04a6e6620169","pre_message_id":"66c10415405d04a6e6620168","role":"assistant","content":{"type":"token","data":{"content":"\u003c|endoftext|\u003e"}},"user_context":{},"user_option":{}}
```


## judge

'''
https://ads.tiktok.com/business-chatbot/event/judge?biz_type=1
{"events":["portrait"]}




{
    "code": 0,
    "msg": "",
    "data": {
        "list": [
            {
                "event": "portrait",
                "configs": {
                    "show_portrait": false
                }
            }
        ]
    }
}
'''
