# params 
 {'predict_dates': [{'start': '2026-05-26', 'end': '2026-05-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260526_18 991608103836495772 (Recorders: 3/5)

	Recorder: b641eb599bb94fcc878e08088a59efc4

		Model: {'id': 'b641eb599bb94fcc878e08088a59efc4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.029, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-05-26', '2025-05-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.167', 'weight': '0.050'}

	Recorder: 655f5c57340d4cfcb049c3061fa6f577

		Model: {'id': '655f5c57340d4cfcb049c3061fa6f577', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.057, 'Rank IC': 0.028, 'Rank ICIR': 0.177}, 'data_train_vec': ['2023-05-26', '2025-08-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.177', 'weight': '0.053'}

	Recorder: 7aa2c1d273b542c3a1d1d5ae479befc0

		Model: {'id': '7aa2c1d273b542c3a1d1d5ae479befc0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.042, 'ICIR': 0.193, 'Rank IC': 0.035, 'Rank ICIR': 0.191}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.191', 'weight': '0.057'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260526_18 992212111400495975 (Recorders: 3/5)

	Recorder: bcec01a85def4399befa1080f47a5501

		Model: {'id': 'bcec01a85def4399befa1080f47a5501', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.198, 'Rank IC': 0.029, 'Rank ICIR': 0.236}, 'data_train_vec': ['2023-05-26', '2025-08-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.236', 'weight': '0.071'}

	Recorder: 2b93e8145a0545ac8dde521f781444f1

		Model: {'id': '2b93e8145a0545ac8dde521f781444f1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.2, 'Rank IC': 0.01, 'Rank ICIR': 0.084}, 'data_train_vec': ['2024-05-26', '2025-11-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.084', 'weight': '0.025'}

	Recorder: 4c86723b64594837b5f55ecc90964330

		Model: {'id': '4c86723b64594837b5f55ecc90964330', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.085, 'ICIR': 0.451, 'Rank IC': 0.045, 'Rank ICIR': 0.217}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.217', 'weight': '0.065'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260526_16 243878110989169351 (Recorders: 4/5)

	Recorder: 1dc51bb22151419380848657bd3cceb0

		Model: {'id': '1dc51bb22151419380848657bd3cceb0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.03, 'Rank ICIR': 0.202}, 'data_train_vec': ['2021-05-26', '2025-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.202', 'weight': '0.061'}

	Recorder: fe3ed01628694a3b8c1ed334efe35f28

		Model: {'id': 'fe3ed01628694a3b8c1ed334efe35f28', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.049, 'Rank IC': 0.037, 'Rank ICIR': 0.21}, 'data_train_vec': ['2022-05-26', '2025-05-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.210', 'weight': '0.063'}

	Recorder: d46acd05a8b244e1840770c9b7bdadbf

		Model: {'id': 'd46acd05a8b244e1840770c9b7bdadbf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.179, 'Rank IC': 0.041, 'Rank ICIR': 0.274}, 'data_train_vec': ['2023-05-26', '2025-08-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.274', 'weight': '0.082'}

	Recorder: 59b448fbaa1d4df6bc48149aeabeedcd

		Model: {'id': '59b448fbaa1d4df6bc48149aeabeedcd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.339, 'Rank IC': 0.036, 'Rank ICIR': 0.2}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.200', 'weight': '0.060'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260526_16 921203255731036381 (Recorders: 4/5)

	Recorder: c011a6eb06d549729c55677f783f581c

		Model: {'id': 'c011a6eb06d549729c55677f783f581c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.059, 'Rank IC': 0.032, 'Rank ICIR': 0.278}, 'data_train_vec': ['2021-05-26', '2025-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.278', 'weight': '0.083'}

	Recorder: b1a493c43e3f4e2188fccc59466acef0

		Model: {'id': 'b1a493c43e3f4e2188fccc59466acef0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.108, 'Rank IC': 0.038, 'Rank ICIR': 0.345}, 'data_train_vec': ['2023-05-26', '2025-08-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.345', 'weight': '0.103'}

	Recorder: d659b0c470b64201853a17143d3fff06

		Model: {'id': 'd659b0c470b64201853a17143d3fff06', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.023, 'Rank IC': 0.011, 'Rank ICIR': 0.087}, 'data_train_vec': ['2024-05-26', '2025-11-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.087', 'weight': '0.026'}

	Recorder: 3156b2e58015419da5c3e649004bba5c

		Model: {'id': '3156b2e58015419da5c3e649004bba5c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.104, 'ICIR': 0.604, 'Rank IC': 0.081, 'Rank ICIR': 0.412}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.412', 'weight': '0.124'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260526_16 351687843325836254 (Recorders: 1/5)

	Recorder: 3949b644f365432e8a00a748c14f7d9b

		Model: {'id': '3949b644f365432e8a00a748c14f7d9b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.302, 'Rank IC': 0.038, 'Rank ICIR': 0.255}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26'], 'rank_icir': '0.255', 'weight': '0.076'}
