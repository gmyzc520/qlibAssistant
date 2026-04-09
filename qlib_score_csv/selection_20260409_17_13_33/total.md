# params 
 {'predict_dates': [{'start': '2026-04-09', 'end': '2026-04-09'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260409_16 918802905810858973 (Recorders: 1/5)

	Recorder: dfce202aa7fa400399c65a3fced6392b

		Model: {'id': 'dfce202aa7fa400399c65a3fced6392b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.233, 'Rank IC': 0.045, 'Rank ICIR': 0.29}, 'data_train_vec': ['2023-04-09', '2025-07-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.290', 'weight': '0.124'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260409_16 584396034507448712 (Recorders: 1/5)

	Recorder: 6e3bee32cd9344869caa7d47da418471

		Model: {'id': '6e3bee32cd9344869caa7d47da418471', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.251, 'Rank IC': 0.036, 'Rank ICIR': 0.313}, 'data_train_vec': ['2024-04-09', '2025-10-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.313', 'weight': '0.133'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260409_14 724667428666332768 (Recorders: 3/5)

	Recorder: c639aa78b01044f0992221e661ee8727

		Model: {'id': 'c639aa78b01044f0992221e661ee8727', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.076, 'Rank IC': 0.03, 'Rank ICIR': 0.164}, 'data_train_vec': ['2021-04-09', '2025-01-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.164', 'weight': '0.070'}

	Recorder: 2ec15f5f63b24ba2a81f22437c2d3e53

		Model: {'id': '2ec15f5f63b24ba2a81f22437c2d3e53', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.148, 'Rank IC': 0.057, 'Rank ICIR': 0.335}, 'data_train_vec': ['2023-04-09', '2025-07-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.335', 'weight': '0.143'}

	Recorder: e42721917288422d9054aeb0248b5068

		Model: {'id': 'e42721917288422d9054aeb0248b5068', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.293, 'Rank IC': 0.033, 'Rank ICIR': 0.321}, 'data_train_vec': ['2024-04-09', '2025-10-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.321', 'weight': '0.137'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260409_14 662210292248184749 (Recorders: 5/5)

	Recorder: fd62b0dddb9646a288067505821a359a

		Model: {'id': 'fd62b0dddb9646a288067505821a359a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.088, 'Rank IC': 0.019, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-04-09', '2025-01-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.156', 'weight': '0.066'}

	Recorder: 50d3f01270ed4d11a6278d42863cc1cf

		Model: {'id': '50d3f01270ed4d11a6278d42863cc1cf', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.017, 'Rank ICIR': 0.147}, 'data_train_vec': ['2022-04-09', '2025-04-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.147', 'weight': '0.063'}

	Recorder: 16134038d4c14cefb95a9aee43436204

		Model: {'id': '16134038d4c14cefb95a9aee43436204', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.149, 'Rank IC': 0.042, 'Rank ICIR': 0.36}, 'data_train_vec': ['2023-04-09', '2025-07-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.360', 'weight': '0.153'}

	Recorder: 0b70d9c09cd04fdfba5fa5eb38c3f632

		Model: {'id': '0b70d9c09cd04fdfba5fa5eb38c3f632', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.052, 'Rank IC': 0.011, 'Rank ICIR': 0.087}, 'data_train_vec': ['2024-04-09', '2025-10-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.087', 'weight': '0.037'}

	Recorder: 906c340e8428460db1b0dbeb9876fbbc

		Model: {'id': '906c340e8428460db1b0dbeb9876fbbc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.088, 'Rank IC': 0.009, 'Rank ICIR': 0.063}, 'data_train_vec': ['2025-04-09', '2026-01-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.063', 'weight': '0.027'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260409_14 964272766621043926 (Recorders: 1/5)

	Recorder: 1e71bbcb06ca46cd8846b2fee261013b

		Model: {'id': '1e71bbcb06ca46cd8846b2fee261013b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.021, 'Rank ICIR': 0.112}, 'data_train_vec': ['2021-04-09', '2025-01-08'], 'train_time_vec': ['2026-04-09', '2026-04-09'], 'rank_icir': '0.112', 'weight': '0.048'}
