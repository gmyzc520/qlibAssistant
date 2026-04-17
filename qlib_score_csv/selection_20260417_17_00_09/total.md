# params 
 {'predict_dates': [{'start': '2026-04-17', 'end': '2026-04-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260417_16 658567057251352901 (Recorders: 3/5)

	Recorder: f920896e505140b2abb8b3bccd97e3ff

		Model: {'id': 'f920896e505140b2abb8b3bccd97e3ff', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.162, 'Rank IC': 0.033, 'Rank ICIR': 0.21}, 'data_train_vec': ['2023-04-17', '2025-07-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.210', 'weight': '0.084'}

	Recorder: 1af556a3d9ce44ecb07cf8ff613b0ca3

		Model: {'id': '1af556a3d9ce44ecb07cf8ff613b0ca3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.059, 'Rank IC': 0.034, 'Rank ICIR': 0.261}, 'data_train_vec': ['2024-04-17', '2025-10-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.261', 'weight': '0.105'}

	Recorder: 55a9c66f923a4b6a93fd453939402484

		Model: {'id': '55a9c66f923a4b6a93fd453939402484', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.21, 'Rank IC': 0.033, 'Rank ICIR': 0.243}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.243', 'weight': '0.098'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260417_16 959478161518386255 (Recorders: 2/5)

	Recorder: d8ef13eb48b145e4921c78e276b6b7fc

		Model: {'id': 'd8ef13eb48b145e4921c78e276b6b7fc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.157, 'Rank IC': 0.031, 'Rank ICIR': 0.243}, 'data_train_vec': ['2024-04-17', '2025-10-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.243', 'weight': '0.098'}

	Recorder: 0d6a6cd6d0254b78b7e0a87bd6f70f3c

		Model: {'id': '0d6a6cd6d0254b78b7e0a87bd6f70f3c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.045, 'ICIR': 0.379, 'Rank IC': 0.031, 'Rank ICIR': 0.244}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.244', 'weight': '0.098'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260417_14 785386735860650472 (Recorders: 3/5)

	Recorder: 249a57f417e045f4988b32d8b10b9710

		Model: {'id': '249a57f417e045f4988b32d8b10b9710', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.057, 'Rank IC': 0.041, 'Rank ICIR': 0.239}, 'data_train_vec': ['2023-04-17', '2025-07-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.239', 'weight': '0.096'}

	Recorder: 37e14abcb2054d9e855463c5639af9cc

		Model: {'id': '37e14abcb2054d9e855463c5639af9cc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.123, 'Rank IC': 0.028, 'Rank ICIR': 0.224}, 'data_train_vec': ['2024-04-17', '2025-10-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.224', 'weight': '0.090'}

	Recorder: e2cdc147331f4e6f8933c8c428fd08cf

		Model: {'id': 'e2cdc147331f4e6f8933c8c428fd08cf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.187, 'Rank IC': 0.021, 'Rank ICIR': 0.112}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.112', 'weight': '0.045'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260417_14 286920095133162442 (Recorders: 2/5)

	Recorder: a222e8fa12c24048a7b588c6560a4565

		Model: {'id': 'a222e8fa12c24048a7b588c6560a4565', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.014, 'Rank ICIR': 0.123}, 'data_train_vec': ['2021-04-17', '2025-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.123', 'weight': '0.049'}

	Recorder: 5f3f8e8fc6e7421aa623b191666463f5

		Model: {'id': '5f3f8e8fc6e7421aa623b191666463f5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.053, 'ICIR': 0.365, 'Rank IC': 0.04, 'Rank ICIR': 0.271}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.271', 'weight': '0.109'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260417_13 878901023982297879 (Recorders: 2/5)

	Recorder: 5c902ab6ab754aabbb7e29e51a76634a

		Model: {'id': '5c902ab6ab754aabbb7e29e51a76634a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.125, 'Rank IC': 0.028, 'Rank ICIR': 0.263}, 'data_train_vec': ['2024-04-17', '2025-10-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.263', 'weight': '0.106'}

	Recorder: d697b94d2d064178bb60094b7419cc7c

		Model: {'id': 'd697b94d2d064178bb60094b7419cc7c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.102, 'Rank IC': 0.009, 'Rank ICIR': 0.056}, 'data_train_vec': ['2025-04-17', '2026-01-16'], 'train_time_vec': ['2026-04-17', '2026-04-17'], 'rank_icir': '0.056', 'weight': '0.022'}
