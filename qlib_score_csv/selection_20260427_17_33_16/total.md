# params 
 {'predict_dates': [{'start': '2026-04-27', 'end': '2026-04-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260427_17 907230580248579866 (Recorders: 2/5)

	Recorder: 951de4ab392e4a7dafdd180f580afae0

		Model: {'id': '951de4ab392e4a7dafdd180f580afae0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.045, 'Rank IC': 0.027, 'Rank ICIR': 0.161}, 'data_train_vec': ['2023-04-27', '2025-07-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.161', 'weight': '0.102'}

	Recorder: 6af2046f13f347849d34f5c885a9860c

		Model: {'id': '6af2046f13f347849d34f5c885a9860c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.154, 'Rank IC': 0.003, 'Rank ICIR': 0.02}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.020', 'weight': '0.013'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260427_17 753532284186344617 (Recorders: 3/5)

	Recorder: b4a23db26d8f4018b3da375cc3b75dc8

		Model: {'id': 'b4a23db26d8f4018b3da375cc3b75dc8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.048, 'Rank IC': 0.03, 'Rank ICIR': 0.211}, 'data_train_vec': ['2023-04-27', '2025-07-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.211', 'weight': '0.133'}

	Recorder: 14165ec8879e4dc89a912bddf9f3f546

		Model: {'id': '14165ec8879e4dc89a912bddf9f3f546', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.057, 'Rank IC': 0.015, 'Rank ICIR': 0.121}, 'data_train_vec': ['2024-04-27', '2025-10-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.121', 'weight': '0.076'}

	Recorder: 072efd3462f14161a1a31e495b9dc897

		Model: {'id': '072efd3462f14161a1a31e495b9dc897', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.24, 'Rank IC': 0.021, 'Rank ICIR': 0.136}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.136', 'weight': '0.086'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260427_14 130086407797823250 (Recorders: 3/5)

	Recorder: 60491ec636884c6191e2a7ee24b01419

		Model: {'id': '60491ec636884c6191e2a7ee24b01419', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.1, 'Rank IC': 0.044, 'Rank ICIR': 0.263}, 'data_train_vec': ['2023-04-27', '2025-07-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.263', 'weight': '0.166'}

	Recorder: 5315c2f4e9c144c7a25ec78600876fd6

		Model: {'id': '5315c2f4e9c144c7a25ec78600876fd6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.063, 'Rank IC': 0.008, 'Rank ICIR': 0.071}, 'data_train_vec': ['2024-04-27', '2025-10-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.071', 'weight': '0.045'}

	Recorder: 18d71100ac35440b88a442a1f9b9589b

		Model: {'id': '18d71100ac35440b88a442a1f9b9589b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.161, 'Rank IC': 0.005, 'Rank ICIR': 0.028}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.028', 'weight': '0.018'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260427_14 927851229252144997 (Recorders: 2/5)

	Recorder: 73fac952ab304dc38f0ee9ce1ebe70aa

		Model: {'id': '73fac952ab304dc38f0ee9ce1ebe70aa', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.009, 'Rank ICIR': 0.072}, 'data_train_vec': ['2024-04-27', '2025-10-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.072', 'weight': '0.045'}

	Recorder: 6728da6ea5464f28b762afadff11dbc2

		Model: {'id': '6728da6ea5464f28b762afadff11dbc2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.057, 'ICIR': 0.452, 'Rank IC': 0.032, 'Rank ICIR': 0.223}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.223', 'weight': '0.141'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260427_14 299213627737995002 (Recorders: 2/5)

	Recorder: e6f404f3c9a44a22824b30e47107a9cf

		Model: {'id': 'e6f404f3c9a44a22824b30e47107a9cf', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.081, 'Rank IC': 0.029, 'Rank ICIR': 0.265}, 'data_train_vec': ['2024-04-27', '2025-10-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.265', 'weight': '0.167'}

	Recorder: d34e3f09c9034b2c8ceed0858bb07d20

		Model: {'id': 'd34e3f09c9034b2c8ceed0858bb07d20', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.055, 'Rank IC': 0.002, 'Rank ICIR': 0.012}, 'data_train_vec': ['2025-04-27', '2026-01-26'], 'train_time_vec': ['2026-04-27', '2026-04-27'], 'rank_icir': '0.012', 'weight': '0.008'}
