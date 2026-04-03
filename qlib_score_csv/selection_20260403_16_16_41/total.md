# params 
 {'predict_dates': [{'start': '2026-04-03', 'end': '2026-04-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260403_15 480934365803857637 (Recorders: 3/5)

	Recorder: 49dad708c3664a4b8e7b669128689d02

		Model: {'id': '49dad708c3664a4b8e7b669128689d02', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.077, 'Rank IC': 0.027, 'Rank ICIR': 0.153}, 'data_train_vec': ['2021-04-03', '2025-01-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.153', 'weight': '0.044'}

	Recorder: 84e45ad53c1748b3a53e1f4f10b6b526

		Model: {'id': '84e45ad53c1748b3a53e1f4f10b6b526', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.204, 'Rank IC': 0.048, 'Rank ICIR': 0.324}, 'data_train_vec': ['2023-04-03', '2025-07-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.324', 'weight': '0.094'}

	Recorder: 831e7458180d487f9eeb9f5ecf1f54b9

		Model: {'id': '831e7458180d487f9eeb9f5ecf1f54b9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.13, 'Rank IC': 0.047, 'Rank ICIR': 0.392}, 'data_train_vec': ['2024-04-03', '2025-10-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.392', 'weight': '0.113'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260403_15 846157198372000433 (Recorders: 3/5)

	Recorder: d55c29a9e1384a35bc3df1e166c61990

		Model: {'id': 'd55c29a9e1384a35bc3df1e166c61990', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.027, 'Rank IC': 0.029, 'Rank ICIR': 0.178}, 'data_train_vec': ['2021-04-03', '2025-01-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.178', 'weight': '0.051'}

	Recorder: 146eb09f488f44ecacdbe61f0229a501

		Model: {'id': '146eb09f488f44ecacdbe61f0229a501', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.063, 'Rank IC': 0.052, 'Rank ICIR': 0.305}, 'data_train_vec': ['2023-04-03', '2025-07-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.305', 'weight': '0.088'}

	Recorder: 1bbc9807ef304e6c80e6f1b6a4cbfcba

		Model: {'id': '1bbc9807ef304e6c80e6f1b6a4cbfcba', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.181, 'Rank IC': 0.027, 'Rank ICIR': 0.234}, 'data_train_vec': ['2024-04-03', '2025-10-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.234', 'weight': '0.068'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260403_13 534218506691185809 (Recorders: 4/5)

	Recorder: 4ba499df91814d73b24bb6ec8aa8528d

		Model: {'id': '4ba499df91814d73b24bb6ec8aa8528d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.113, 'Rank IC': 0.04, 'Rank ICIR': 0.224}, 'data_train_vec': ['2021-04-03', '2025-01-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.224', 'weight': '0.065'}

	Recorder: c707680442ef40998cb0e92012115e5e

		Model: {'id': 'c707680442ef40998cb0e92012115e5e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.009, 'Rank IC': 0.028, 'Rank ICIR': 0.153}, 'data_train_vec': ['2022-04-03', '2025-04-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.153', 'weight': '0.044'}

	Recorder: 463d21fc67b14f61a90a3a394bfa3a22

		Model: {'id': '463d21fc67b14f61a90a3a394bfa3a22', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.108, 'Rank IC': 0.053, 'Rank ICIR': 0.302}, 'data_train_vec': ['2023-04-03', '2025-07-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.302', 'weight': '0.087'}

	Recorder: ec5cdac7d739471abdf19f0d3af57220

		Model: {'id': 'ec5cdac7d739471abdf19f0d3af57220', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.225, 'Rank IC': 0.032, 'Rank ICIR': 0.319}, 'data_train_vec': ['2024-04-03', '2025-10-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.319', 'weight': '0.092'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260403_13 641602740652538756 (Recorders: 3/5)

	Recorder: 5ab3a61f90d647e883b5e9445f72595a

		Model: {'id': '5ab3a61f90d647e883b5e9445f72595a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.106, 'Rank IC': 0.024, 'Rank ICIR': 0.199}, 'data_train_vec': ['2021-04-03', '2025-01-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.199', 'weight': '0.057'}

	Recorder: 3e6821a2854549acbf7089a043a7f7ea

		Model: {'id': '3e6821a2854549acbf7089a043a7f7ea', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.028, 'Rank IC': 0.021, 'Rank ICIR': 0.177}, 'data_train_vec': ['2022-04-03', '2025-04-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.177', 'weight': '0.051'}

	Recorder: b2702e8611f749c989689ae7c506dcf6

		Model: {'id': 'b2702e8611f749c989689ae7c506dcf6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.097, 'Rank IC': 0.039, 'Rank ICIR': 0.33}, 'data_train_vec': ['2023-04-03', '2025-07-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.330', 'weight': '0.095'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260403_13 797869000914679144 (Recorders: 1/5)

	Recorder: 919b1ed074e544ccba069335be46328d

		Model: {'id': '919b1ed074e544ccba069335be46328d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.043, 'Rank IC': 0.031, 'Rank ICIR': 0.175}, 'data_train_vec': ['2022-04-03', '2025-04-02'], 'train_time_vec': ['2026-04-03', '2026-04-03'], 'rank_icir': '0.175', 'weight': '0.051'}
