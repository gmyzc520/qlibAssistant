# params 
 {'predict_dates': [{'start': '2026-04-20', 'end': '2026-04-20'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260420_16 182551140467581533 (Recorders: 3/5)

	Recorder: eac6abacb4b44e7c8d221581b6631375

		Model: {'id': 'eac6abacb4b44e7c8d221581b6631375', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.306, 'Rank IC': 0.04, 'Rank ICIR': 0.26}, 'data_train_vec': ['2023-04-20', '2025-07-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.260', 'weight': '0.107'}

	Recorder: 25999b6805de45d699c1b89ff85926d6

		Model: {'id': '25999b6805de45d699c1b89ff85926d6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.067, 'Rank IC': 0.034, 'Rank ICIR': 0.232}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.232', 'weight': '0.096'}

	Recorder: 0ec8ed665b2d4df38893014760976cde

		Model: {'id': '0ec8ed665b2d4df38893014760976cde', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.235, 'Rank IC': 0.011, 'Rank ICIR': 0.111}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.111', 'weight': '0.046'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260420_16 800951335655377545 (Recorders: 2/5)

	Recorder: 2812285f8f1d4b858d8ad8929d58cf6b

		Model: {'id': '2812285f8f1d4b858d8ad8929d58cf6b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.186, 'Rank IC': 0.034, 'Rank ICIR': 0.287}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.287', 'weight': '0.118'}

	Recorder: 322e80a494944cbba77a6e41ecb1ff2e

		Model: {'id': '322e80a494944cbba77a6e41ecb1ff2e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.207, 'Rank IC': 0.016, 'Rank ICIR': 0.117}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.117', 'weight': '0.048'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260420_14 963154356900779206 (Recorders: 3/5)

	Recorder: c1dff00ee77d4d30a86fddf33ad02082

		Model: {'id': 'c1dff00ee77d4d30a86fddf33ad02082', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.06, 'Rank IC': 0.045, 'Rank ICIR': 0.262}, 'data_train_vec': ['2023-04-20', '2025-07-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.262', 'weight': '0.108'}

	Recorder: 61e81080ca8242a69a2b865755651c33

		Model: {'id': '61e81080ca8242a69a2b865755651c33', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.132, 'Rank IC': 0.021, 'Rank ICIR': 0.171}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.171', 'weight': '0.071'}

	Recorder: 42e813a2922b4e659611425e24030b41

		Model: {'id': '42e813a2922b4e659611425e24030b41', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.303, 'Rank IC': 0.031, 'Rank ICIR': 0.168}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.168', 'weight': '0.069'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260420_14 180197432253793345 (Recorders: 2/5)

	Recorder: dacbb6ac869e4d5480e52caafaf08dc9

		Model: {'id': 'dacbb6ac869e4d5480e52caafaf08dc9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.013, 'Rank ICIR': 0.106}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.106', 'weight': '0.044'}

	Recorder: 918063b1110f4a6da3c8c28c25f27886

		Model: {'id': '918063b1110f4a6da3c8c28c25f27886', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.068, 'ICIR': 0.465, 'Rank IC': 0.049, 'Rank ICIR': 0.332}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.332', 'weight': '0.137'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260420_14 110061519876569829 (Recorders: 2/5)

	Recorder: 898fcb1d6b044f39a0f8910e8ba5f861

		Model: {'id': '898fcb1d6b044f39a0f8910e8ba5f861', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.076, 'Rank IC': 0.03, 'Rank ICIR': 0.257}, 'data_train_vec': ['2024-04-20', '2025-10-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.257', 'weight': '0.106'}

	Recorder: e58f076079b040789bd0d4063a485e2b

		Model: {'id': 'e58f076079b040789bd0d4063a485e2b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.064, 'ICIR': 0.42, 'Rank IC': 0.019, 'Rank ICIR': 0.12}, 'data_train_vec': ['2025-04-20', '2026-01-19'], 'train_time_vec': ['2026-04-20', '2026-04-20'], 'rank_icir': '0.120', 'weight': '0.050'}
