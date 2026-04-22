# params 
 {'predict_dates': [{'start': '2026-04-22', 'end': '2026-04-22'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260422_16 656752879100633094 (Recorders: 2/5)

	Recorder: 63768b4ccc0c4733b17487d8314d713d

		Model: {'id': '63768b4ccc0c4733b17487d8314d713d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.248, 'Rank IC': 0.047, 'Rank ICIR': 0.277}, 'data_train_vec': ['2023-04-22', '2025-07-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.277', 'weight': '0.150'}

	Recorder: 2eda694597dc4d529867ac4f7a461cdf

		Model: {'id': '2eda694597dc4d529867ac4f7a461cdf', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.074, 'ICIR': 0.578, 'Rank IC': 0.031, 'Rank ICIR': 0.211}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.211', 'weight': '0.114'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260422_16 266890662104671770 (Recorders: 2/5)

	Recorder: 36328a3974584bf8be58f67a696ef6d2

		Model: {'id': '36328a3974584bf8be58f67a696ef6d2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.226, 'Rank IC': 0.037, 'Rank ICIR': 0.29}, 'data_train_vec': ['2024-04-22', '2025-10-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.290', 'weight': '0.157'}

	Recorder: 704b3923afd940c881322eeb437cf235

		Model: {'id': '704b3923afd940c881322eeb437cf235', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.36, 'Rank IC': 0.024, 'Rank ICIR': 0.165}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.165', 'weight': '0.089'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260422_14 988745326390030794 (Recorders: 3/5)

	Recorder: 61f91ae1faff4293997bc929ed324f20

		Model: {'id': '61f91ae1faff4293997bc929ed324f20', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.02, 'Rank IC': 0.038, 'Rank ICIR': 0.213}, 'data_train_vec': ['2023-04-22', '2025-07-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.213', 'weight': '0.115'}

	Recorder: a8a4ca4c02fe41458420fac52f503a44

		Model: {'id': 'a8a4ca4c02fe41458420fac52f503a44', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.123, 'Rank IC': 0.022, 'Rank ICIR': 0.177}, 'data_train_vec': ['2024-04-22', '2025-10-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.177', 'weight': '0.096'}

	Recorder: 82a783e5bb1b46a9832781e50c98bb20

		Model: {'id': '82a783e5bb1b46a9832781e50c98bb20', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.251, 'Rank IC': 0.014, 'Rank ICIR': 0.078}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.078', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260422_14 367874509472298573 (Recorders: 1/5)

	Recorder: f8de4d1bc86b4278b654add18fe9770e

		Model: {'id': 'f8de4d1bc86b4278b654add18fe9770e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.406, 'Rank IC': 0.033, 'Rank ICIR': 0.245}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.245', 'weight': '0.133'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260422_14 788946692601649505 (Recorders: 1/5)

	Recorder: 43cc3f40b44d46fb8e799d746bb942d4

		Model: {'id': '43cc3f40b44d46fb8e799d746bb942d4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.322, 'Rank IC': 0.033, 'Rank ICIR': 0.192}, 'data_train_vec': ['2025-04-22', '2026-01-21'], 'train_time_vec': ['2026-04-22', '2026-04-22'], 'rank_icir': '0.192', 'weight': '0.104'}
