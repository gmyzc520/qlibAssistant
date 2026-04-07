# params 
 {'predict_dates': [{'start': '2026-04-07', 'end': '2026-04-07'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260407_16 232957148624436742 (Recorders: 4/5)

	Recorder: 8810067823454f42b8dc1a3e8fdb8e86

		Model: {'id': '8810067823454f42b8dc1a3e8fdb8e86', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.048, 'Rank IC': 0.025, 'Rank ICIR': 0.135}, 'data_train_vec': ['2021-04-07', '2025-01-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.135', 'weight': '0.036'}

	Recorder: f00c6b34287845fba2969f0ef8bfd819

		Model: {'id': 'f00c6b34287845fba2969f0ef8bfd819', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.011, 'Rank IC': 0.034, 'Rank ICIR': 0.182}, 'data_train_vec': ['2022-04-07', '2025-04-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.182', 'weight': '0.048'}

	Recorder: 3d398f4773e046c2892ac97b676f83f4

		Model: {'id': '3d398f4773e046c2892ac97b676f83f4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.072, 'Rank IC': 0.048, 'Rank ICIR': 0.364}, 'data_train_vec': ['2023-04-07', '2025-07-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.364', 'weight': '0.096'}

	Recorder: 547549e6466447d58bd0906dc30beab5

		Model: {'id': '547549e6466447d58bd0906dc30beab5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.322, 'Rank IC': 0.039, 'Rank ICIR': 0.336}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.336', 'weight': '0.088'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260407_16 300730131598105522 (Recorders: 1/5)

	Recorder: 1a307dfd78ae4747b26a995c46909327

		Model: {'id': '1a307dfd78ae4747b26a995c46909327', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.302, 'Rank IC': 0.037, 'Rank ICIR': 0.312}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.312', 'weight': '0.082'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260407_14 224363339602305547 (Recorders: 4/5)

	Recorder: d5d17f088e6840b9bfd9a7f60ae12af4

		Model: {'id': 'd5d17f088e6840b9bfd9a7f60ae12af4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.067, 'Rank IC': 0.031, 'Rank ICIR': 0.169}, 'data_train_vec': ['2021-04-07', '2025-01-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.169', 'weight': '0.045'}

	Recorder: 87c0ead7fba846b89af49253385b31c3

		Model: {'id': '87c0ead7fba846b89af49253385b31c3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.017, 'Rank IC': 0.031, 'Rank ICIR': 0.168}, 'data_train_vec': ['2022-04-07', '2025-04-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.168', 'weight': '0.044'}

	Recorder: 8a10952492b143a2aa7ee2659e94b3e1

		Model: {'id': '8a10952492b143a2aa7ee2659e94b3e1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.118, 'Rank IC': 0.055, 'Rank ICIR': 0.324}, 'data_train_vec': ['2023-04-07', '2025-07-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.324', 'weight': '0.085'}

	Recorder: f2bbd8c2038247c1a72bb18e43ce9f9f

		Model: {'id': 'f2bbd8c2038247c1a72bb18e43ce9f9f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.358, 'Rank IC': 0.037, 'Rank ICIR': 0.368}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.368', 'weight': '0.097'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260407_14 184180744032580428 (Recorders: 3/5)

	Recorder: 5cb42719069e4aa789c266a3c30b477a

		Model: {'id': '5cb42719069e4aa789c266a3c30b477a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.11, 'Rank IC': 0.023, 'Rank ICIR': 0.187}, 'data_train_vec': ['2021-04-07', '2025-01-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.187', 'weight': '0.049'}

	Recorder: 2b7a4a5db3df46ff86f0f908ede4087b

		Model: {'id': '2b7a4a5db3df46ff86f0f908ede4087b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.054, 'Rank IC': 0.024, 'Rank ICIR': 0.204}, 'data_train_vec': ['2022-04-07', '2025-04-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.204', 'weight': '0.054'}

	Recorder: ab407acb404f4467a6a920e75407666a

		Model: {'id': 'ab407acb404f4467a6a920e75407666a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.101, 'Rank IC': 0.039, 'Rank ICIR': 0.338}, 'data_train_vec': ['2023-04-07', '2025-07-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.338', 'weight': '0.089'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260407_13 303129279589466392 (Recorders: 3/5)

	Recorder: 9d2db4667b0f4f42ae9d1d5a8ffbabbb

		Model: {'id': '9d2db4667b0f4f42ae9d1d5a8ffbabbb', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.048, 'Rank IC': 0.028, 'Rank ICIR': 0.151}, 'data_train_vec': ['2021-04-07', '2025-01-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.151', 'weight': '0.040'}

	Recorder: 26a534cc56cc423eb495189ca87ba5b3

		Model: {'id': '26a534cc56cc423eb495189ca87ba5b3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.087, 'Rank IC': 0.048, 'Rank ICIR': 0.286}, 'data_train_vec': ['2023-04-07', '2025-07-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.286', 'weight': '0.075'}

	Recorder: 33a392ce30514b42be1a53334eb02a5c

		Model: {'id': '33a392ce30514b42be1a53334eb02a5c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.287, 'Rank IC': 0.032, 'Rank ICIR': 0.273}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07'], 'rank_icir': '0.273', 'weight': '0.072'}
