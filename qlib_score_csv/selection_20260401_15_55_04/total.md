# params 
 {'predict_dates': [{'start': '2026-04-01', 'end': '2026-04-01'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260401_15 445386904219318559 (Recorders: 3/5)

	Recorder: d7fa27f50b304858862f1c32a16f11b2

		Model: {'id': 'd7fa27f50b304858862f1c32a16f11b2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.208, 'Rank IC': 0.052, 'Rank ICIR': 0.304}, 'data_train_vec': ['2023-04-01', '2025-06-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.304', 'weight': '0.094'}

	Recorder: dbf43a8294b8420d8afedc40a658d993

		Model: {'id': 'dbf43a8294b8420d8afedc40a658d993', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.135, 'Rank IC': 0.05, 'Rank ICIR': 0.356}, 'data_train_vec': ['2024-04-01', '2025-09-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.356', 'weight': '0.110'}

	Recorder: 44c9a0708f1f4bf38e1d54639ede187e

		Model: {'id': '44c9a0708f1f4bf38e1d54639ede187e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.14, 'Rank IC': 0.009, 'Rank ICIR': 0.069}, 'data_train_vec': ['2025-04-01', '2025-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.069', 'weight': '0.021'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260401_15 868863258345436285 (Recorders: 3/5)

	Recorder: 1f7af03bb5204073a4a702e432a47977

		Model: {'id': '1f7af03bb5204073a4a702e432a47977', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.039, 'Rank IC': 0.027, 'Rank ICIR': 0.158}, 'data_train_vec': ['2021-04-01', '2024-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.158', 'weight': '0.049'}

	Recorder: 1e0e84c7be954ba5b264b943e9eb937b

		Model: {'id': '1e0e84c7be954ba5b264b943e9eb937b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.007, 'Rank IC': 0.044, 'Rank ICIR': 0.228}, 'data_train_vec': ['2023-04-01', '2025-06-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.228', 'weight': '0.071'}

	Recorder: 2fe4d9b884dc4a369645a17ec2b25e8b

		Model: {'id': '2fe4d9b884dc4a369645a17ec2b25e8b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.142, 'Rank IC': 0.03, 'Rank ICIR': 0.256}, 'data_train_vec': ['2024-04-01', '2025-09-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.256', 'weight': '0.079'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260401_12 519701681827210055 (Recorders: 3/5)

	Recorder: 498a74da31184fc48aac00218bd7a719

		Model: {'id': '498a74da31184fc48aac00218bd7a719', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.122, 'Rank IC': 0.04, 'Rank ICIR': 0.218}, 'data_train_vec': ['2021-04-01', '2024-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.218', 'weight': '0.067'}

	Recorder: d283e49ad5294da589302a158a9dcfd3

		Model: {'id': 'd283e49ad5294da589302a158a9dcfd3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.084, 'Rank IC': 0.051, 'Rank ICIR': 0.291}, 'data_train_vec': ['2023-04-01', '2025-06-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.291', 'weight': '0.090'}

	Recorder: 2a41f59b768c4df6b54009ebdff9b7e2

		Model: {'id': '2a41f59b768c4df6b54009ebdff9b7e2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.222, 'Rank IC': 0.033, 'Rank ICIR': 0.31}, 'data_train_vec': ['2024-04-01', '2025-09-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.310', 'weight': '0.096'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260401_12 557675197322138284 (Recorders: 4/5)

	Recorder: e351a8688c504db18365084a54121633

		Model: {'id': 'e351a8688c504db18365084a54121633', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.101, 'Rank IC': 0.023, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-04-01', '2024-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.185', 'weight': '0.057'}

	Recorder: 0aad9805880344fe96155cb2cbf2e8d3

		Model: {'id': '0aad9805880344fe96155cb2cbf2e8d3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.024, 'Rank IC': 0.02, 'Rank ICIR': 0.172}, 'data_train_vec': ['2022-04-01', '2025-03-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.172', 'weight': '0.053'}

	Recorder: 221ff8891c6840548e958fd85f350543

		Model: {'id': '221ff8891c6840548e958fd85f350543', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.116, 'Rank IC': 0.039, 'Rank ICIR': 0.325}, 'data_train_vec': ['2023-04-01', '2025-06-30'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.325', 'weight': '0.101'}

	Recorder: bc73254128154b07aa5c8ae6fd7bedc0

		Model: {'id': 'bc73254128154b07aa5c8ae6fd7bedc0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.054, 'Rank IC': 0.003, 'Rank ICIR': 0.025}, 'data_train_vec': ['2025-04-01', '2025-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.025', 'weight': '0.008'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260401_12 677919348078084190 (Recorders: 2/5)

	Recorder: 78426fbda9de422492cc201bc97874da

		Model: {'id': '78426fbda9de422492cc201bc97874da', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.118, 'Rank IC': 0.034, 'Rank ICIR': 0.181}, 'data_train_vec': ['2021-04-01', '2024-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.181', 'weight': '0.056'}

	Recorder: 098b9a4c6ff343a5b1257a4ddd332459

		Model: {'id': '098b9a4c6ff343a5b1257a4ddd332459', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.12, 'Rank IC': 0.014, 'Rank ICIR': 0.155}, 'data_train_vec': ['2025-04-01', '2025-12-31'], 'train_time_vec': ['2026-04-01', '2026-04-01'], 'rank_icir': '0.155', 'weight': '0.048'}
